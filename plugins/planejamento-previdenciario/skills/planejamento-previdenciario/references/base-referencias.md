# Base de referências do escritório (timbre, orientações fixas e banco de dados local)

A skill usa dois locais de material do escritório já validado, independentes
da pasta do caso enviada nesta conversa, compartilhados com a skill
`pecas-previdenciarias-escritorio`:

- **`referencias-escritorio/`** (dentro do repositório da skill, versionado
  no GitHub): só orientações gerais fixas e as regras comuns de estilo/
  formatação/citação (`regras-comuns/`).
- **`C:\Users\Administrador\Desktop\CCL\Base de Referências\`** (pasta local
  neste computador, **fora do repositório da skill, nunca commitada nem
  enviada ao GitHub**): o banco de dados que cresce a cada peça/parecer —
  lei/jurisprudência por matéria, doutrina salva, modelos, parágrafos e o
  timbre padrão do escritório.

**Timbre padrão.** `C:\Users\Administrador\Desktop\CCL\Base de
Referências\modelo-timbre\modelo-timbre-escritorio.docx` contém o modelo
oficial de timbre/formatação do escritório. Se o usuário não enviar um
modelo próprio do escritório para este planejamento, use esse arquivo como
timbre padrão, avisando o usuário de que está usando o padrão do escritório,
em vez de pausar o fluxo pedindo o modelo.

**Orientações gerais do escritório.** `referencias-escritorio/orientacoes-gerais.md`
reúne regras de bastidor válidas para qualquer matéria (ex.: honorários
geralmente não devidos em primeiro grau nos Juizados Especiais Federais).
Como o parecer é consultivo e não formula pedidos a um juízo, a maior parte
dessas orientações não se aplica diretamente aqui: mas, se o planejamento
mencionar uma futura via judicial ou administrativa como parte da estratégia
recomendada, consulte esse arquivo como checagem de bastidor, aplicando a
mesma parcimônia de linguagem já exigida para lei/jurisprudência abaixo.

**Consulta ativa do banco de dados local, no início de todo planejamento.**
Assim que a matéria/benefício específico do caso estiver claro, abra a
subpasta correspondente em
`C:\Users\Administrador\Desktop\CCL\Base de Referências\previdenciario\[matéria]\`
e faça uma análise ativa de pertinência: compare os fatos e a estratégia do
caso concreto com o que estiver salvo lá (lei/jurisprudência do
`base-conhecimento.md`, doutrina em `doutrina/`), em vez de só abrir o
arquivo por abrir.

**Leis e jurisprudência já validadas.** A pasta local tem subpastas por
matéria dentro de `previdenciario/` (ex.: `auxilio-doenca/`, `loas/`), cada
uma com um arquivo `base-conhecimento.md` reunindo trechos de lei,
jurisprudência e direcionamentos gerais já validados em peças e
planejamentos anteriores, no formato definido em
`_MODELO-formato-base-conhecimento.md` (na raiz da pasta local: Índice de
títulos/tags no topo + entradas padronizadas), além de uma subpasta
`doutrina/` opcional em cada matéria com os arquivos originais de doutrina
já salvos (ver "Doutrina salva por matéria" em
`pecas-previdenciarias-escritorio/references/base-referencias.md`, que usa a
mesma pasta compartilhada).
- Use esse material apenas como **checagem de bastidor** para garantir que a
  explicação de uma regra, requisito ou tese está tecnicamente correta:
  nunca como conteúdo a despejar no parecer.
- **Parcimônia é obrigatória aqui, mais do que nas peças processuais.** O
  público do parecer é o cliente leigo, não um juízo. Não cite lei ou
  jurisprudência por extenso, não encha o texto de referências normativas, e
  evite citar dispositivo/julgado a cada frase. Quando for necessário
  mencionar a base legal de uma regra (ex.: para dar segurança ao cliente de
  que a orientação tem respaldo), faça isso de forma pontual e em linguagem
  acessível (ex.: "essa regra está prevista na Emenda Constitucional
  103/2019" em vez de citar artigo por artigo): nunca em bloco de citação
  literal.
- Se a subpasta da matéria não existir ou estiver vazia, prossiga apenas com
  o raciocínio técnico já dominado, sem bloquear o fluxo por isso.
- A subpasta `previdenciario/acordos-internacionais/` merece atenção
  especial nesta skill: acordos internacionais de previdência social são
  relevantes sobretudo para planejamento (simulação de cenários que somam
  tempo de contribuição em mais de um país), mais raramente citados numa
  peça processual isolada. Sempre que o caso envolver contribuição ou
  trabalho em outro país, consulte essa subpasta ativamente, mesmo que a
  matéria principal do planejamento seja outra (ex.: aposentadoria por
  tempo de contribuição com período trabalhado em Portugal).

**Orientações operacionais de sistema (Cálculo Jurídico/CJ, Tramitação
Inteligente), por matéria.** Mesma mecânica descrita em
`pecas-previdenciarias-escritorio/references/base-referencias.md`: quando o
usuário fornecer, na pasta do caso, um documento próprio ensinando como
operar o CJ (ou outro sistema) para um procedimento específico de uma
matéria (ex.: como simular uma determinada regra de transição), leia-o,
aplique-o ao montar os cenários deste planejamento, oriente o usuário passo
a passo sobre como proceder no sistema, e ao final grave/atualize
`orientacoes-sistema.md` na subpasta da matéria (mesmo fluxo de "Alimentando
a base" abaixo) para reutilizar em planejamentos futuros do mesmo tipo, sem
precisar que o usuário reenvie o documento. Esse conteúdo é sempre
operacional/interno: nunca aparece nomeado no parecer entregue ao cliente
(ver REGRA DE REFERÊNCIAS AO CLIENTE no SKILL.md).

## Alimentando a base (triagem automática + uma única pergunta resumida)

Depois que o usuário aprovar o parecer final (ETAPA 6 — Revisão), a própria
skill faz a triagem do que vale salvar, em vez de perguntar de forma aberta:
tudo gravado diretamente em
`C:\Users\Administrador\Desktop\CCL\Base de Referências\`, nunca no
repositório da skill:

1. **Levante os candidatos.** Percorra os trechos de lei/jurisprudência
   usados na fundamentação do parecer e identifique quais têm potencial de
   reaparecer em planejamentos ou peças futuros da mesma matéria (descarte
   teses genéricas demais para virar entrada, ou hiperespecíficas demais
   para se repetir com outro cliente). Inclua também, quando aplicável,
   orientação de como operar o CJ/Tramitação Inteligente para um
   procedimento desta matéria (ver acima), se o usuário tiver fornecido esse
   tipo de documento e ela ainda não estiver salva em
   `orientacoes-sistema.md`.
2. **Verifique duplicidade antes de propor.** Para cada candidato, confira o
   Índice do `base-conhecimento.md` da matéria (ver
   `_MODELO-formato-base-conhecimento.md`, na raiz da pasta local). Descarte
   silenciosamente, sem levar à pergunta, qualquer candidato que já tenha
   entrada equivalente na base sem nuance nova a acrescentar.
3. **Pergunta única, já pré-filtrada.** Apresente apenas o que sobrou do
   filtro, numa lista curta:
   > "Este parecer trouxe [N] pontos com potencial de reforçar a base do
   > escritório: [título curto 1], [título curto 2]... Aprova salvar em
   > `Base de Referências\previdenciario\[matéria]\base-conhecimento.md`,
   > quer ajustar algum item, ou prefere não salvar desta vez?"
   Se não houver nenhum candidato depois do filtro, não faça a pergunta:
   apenas informe em uma frase que nada novo foi identificado para a base.
4. **Grave conforme aprovado**, seguindo o formato do template (Índice +
   entrada, com título, tags, data e caso de origem). O corpo da entrada
   nunca é o texto completo do parecer (que é redigido em linguagem
   acessível ao cliente): é a referência legal/jurisprudencial em si
   (tribunal/órgão, número, artigo, data), preservada tal como
   identificada, no mesmo formato que a base compartilhada usa em
   `pecas-previdenciarias-escritorio` (ver
   `_MODELO-formato-base-conhecimento.md`), para que sirva de fonte
   confiável e reutilizável também nas peças processuais, não só no
   próximo parecer. Grave como nova entrada, ou atualize pontualmente uma
   entrada existente com nuance nova (nunca duplicando o mesmo tema). Essa
   gravação é sempre edição direta de arquivo na pasta local: nunca inclua
   esse conteúdo em commit/push do repositório da skill.

O usuário também pode enviar doutrina ou pedir para guardar material na base
a qualquer momento, mesmo fora do fluxo de um planejamento específico:
nesse caso, siga a mesma mecânica descrita em "ENVIO DIRETO PARA A BASE" e
"Doutrina salva por matéria" em
`pecas-previdenciarias-escritorio/references/base-referencias.md`, já que a
pasta local é compartilhada entre as duas skills.
