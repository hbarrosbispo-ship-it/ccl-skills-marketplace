# Base de referências do escritório (timbre, orientações fixas e banco de dados local)

A skill usa dois locais de material do escritório já validado em peças
anteriores, independentes da pasta do caso enviada pelo usuário nesta
conversa. Eles têm naturezas diferentes e nunca devem ser confundidos:

- **`referencias-escritorio/`** (dentro do repositório da skill, versionado
  no GitHub, compartilhado por link com `planejamento-previdenciario`): só
  orientações gerais fixas e as regras comuns de estilo/formatação/citação
  (`regras-comuns/`) — conteúdo de configuração do escritório, que não muda
  caso a caso.
- **`C:\Users\Administrador\Desktop\CCL\Base de Referências\`** (pasta local
  neste computador, **fora do repositório da skill, nunca commitada nem
  enviada ao GitHub**): o banco de dados que cresce a cada peça — lei/
  jurisprudência por matéria, doutrina salva, modelos de peça, modelos de
  parágrafos, endereços de citação e o timbre padrão do escritório. É
  compartilhada com a skill `planejamento-previdenciario`.

**Timbre padrão.** `C:\Users\Administrador\Desktop\CCL\Base de
Referências\modelo-timbre\modelo-timbre-escritorio.docx` contém o modelo
oficial de timbre/formatação do escritório (header, footer, logo e
configuração de página do escritório, com o corpo do documento em branco,
pronto para receber o texto de qualquer peça).
- Se o usuário enviar um modelo próprio na categoria "d" (INSTRUÇÃO DE
  INÍCIO), use o modelo enviado — ele tem prioridade, pois pode refletir uma
  exigência específica daquele caso ou órgão.
- Se a categoria "d" ficar ausente, verifique primeiro se existe um modelo de
  peça salvo para aquela matéria e tipo de peça no banco de dados local (ver
  "Modelos de peça salvos por matéria" abaixo). Se existir, use-o e avise o
  usuário de que está usando o modelo salvo daquela matéria, permitindo que
  ele peça o timbre padrão genérico no lugar, se preferir. Se não existir,
  **não trate isso como bloqueio**: use o arquivo de
  `Base de Referências\modelo-timbre\modelo-timbre-escritorio.docx` como
  timbre padrão, avise o usuário de que está usando o modelo padrão do
  escritório, e siga o fluxo normalmente.

**Orientações gerais do escritório.** `referencias-escritorio/orientacoes-gerais.md`
reúne regras de bastidor que valem para qualquer matéria, não amarradas a uma
tese específica (ex.: honorários advocatícios geralmente não devidos em
primeiro grau nos Juizados Especiais Federais). Trate como fonte confiável,
sem pedir confirmação de autenticidade. Consulte esse arquivo:
- Na Etapa 5 (Estratégia Argumentativa) e na Etapa 8b (Rascunho
  Estruturado), para verificar se alguma orientação geral se aplica ao caso
  antes de propor pedidos ou teses.
- Na Etapa 9, ao redigir "DOS PEDIDOS E REQUERIMENTOS", para aplicar
  orientações que mudam o que é ou não pedido (ex.: omitir pedido de
  honorários de sucumbência de primeiro grau em peça de JEF, conforme
  detalhado nesse arquivo).
Se o arquivo trouxer uma orientação relevante ao caso, aplique-a
silenciosamente na redação (sem precisar perguntar de novo a cada peça,
já que a orientação já foi validada previamente) — mas, se houver
ambiguidade sobre se ela se aplica ao caso concreto (ex.: dúvida se o
processo tramita mesmo em JEF), pergunte ao usuário antes de aplicar ou
descartar.

**Consulta ativa do banco de dados local, no início de toda peça.** Assim
que a matéria e o tema específico do caso estiverem claros (o mais tardar na
ETAPA 7), abra a subpasta correspondente em
`C:\Users\Administrador\Desktop\CCL\Base de Referências\[área]\[matéria]\`
(ex.: `...\previdenciario\loas\`) e faça uma análise ativa de pertinência:
não se limite a abrir o arquivo por abrir — compare os fatos e a tese do
caso concreto com cada item salvo lá (lei/jurisprudência do
`base-conhecimento.md`, doutrina em `doutrina/`, modelos em `modelos-peca/`,
parágrafos em `modelos-paragrafos/`) e identifique especificamente o que é
útil ou importante para este caso. Se a subpasta da matéria não existir ou
estiver vazia, trabalhe apenas com o material que o usuário forneceu nesta
conversa, normalmente.

**Leis e jurisprudência já validadas, por matéria.** A pasta local tem
subpastas por área e matéria (ex.: `previdenciario/auxilio-doenca/`,
`previdenciario/loas/`, `civil/...`, `tributario/...`), cada uma com um
arquivo `base-conhecimento.md` reunindo trechos de lei, jurisprudência e
direcionamentos gerais já usados com segurança em peças anteriores daquela
matéria específica. O formato desse arquivo (Índice de títulos/tags no topo,
seguido de entradas padronizadas) está definido em
`_MODELO-formato-base-conhecimento.md`, na raiz da pasta local — siga sempre
esse modelo ao ler ou gravar uma entrada, nunca um bloco de texto solto.
- Na ETAPA 7 (Análise da Doutrina), além do material que o usuário enviou
  nesta conversa (categoria "c"), consulte também o `base-conhecimento.md`
  da subpasta correspondente à matéria do caso, se existir, e trate o que
  estiver lá como fonte confiável — sem precisar pedir confirmação de
  autenticidade ao usuário novamente, já que esse material só entra ali
  depois de aprovado previamente. Aplique normalmente as RESTRIÇÕES
  ABSOLUTAS e as regras de citação de fontes (`regras-comuns/citacao-fontes.md`)
  sobre como citar (sem transcrição literal, salvo a exceção controlada)
  qualquer que seja a origem do material.

**Doutrina salva por matéria.** Cada subpasta de matéria pode ter uma
subpasta `doutrina/` (ex.: `previdenciario/auxilio-doenca/doutrina/`), com os
próprios arquivos de doutrina (PDF/Word) já enviados pelo usuário em casos
anteriores dessa matéria e guardados para consulta futura — diferente do
resumo em texto que fica no arquivo de lei/jurisprudência da matéria, aqui
fica o documento original, íntegro.
- Sempre que o usuário enviar um documento de doutrina explicitamente para
  "guardar na base" ou "salvar para a matéria" (fora do fluxo de uma peça
  específica, ou ao final da Etapa 10 conforme "Alimentando a base" abaixo),
  salve o arquivo original em
  `C:\Users\Administrador\Desktop\CCL\Base de Referências\[área]\[matéria]\doutrina\`,
  sem alterar seu conteúdo.
- Na ETAPA 7, ao consultar a subpasta da matéria, verifique também se há
  doutrina salva em `doutrina/` e trate-a como fonte adicional, com a mesma
  confiança dada ao material da categoria "c" enviado nesta conversa.
- Se houver muitos arquivos de doutrina salvos na mesma matéria, priorize os
  mais diretamente relacionados aos pontos controvertidos do caso atual, em
  vez de tentar aplicar todos de uma vez.

**Modelos de peça salvos por matéria.** Cada subpasta de matéria pode ter uma
subpasta `modelos-peca/` (ex.: `previdenciario/auxilio-doenca/modelos-peca/`),
com arquivos .docx de peças já elaboradas e aprovadas pelo escritório,
guardados para reutilizar como ponto de partida em casos futuros da mesma
matéria e do mesmo tipo de peça (ex.: `peticao-inicial-auxilio-doenca.docx`,
`recurso-administrativo-bpc-loas.docx`). Nome do arquivo deve indicar
claramente o tipo de peça.
- Sempre que o usuário enviar um modelo de peça explicitamente para "guardar
  na base" ou "salvar para casos futuros dessa matéria" (fora do fluxo de um
  caso específico, ou ao final da Etapa 10 conforme "Alimentando a base"
  abaixo), salve o arquivo em
  `C:\Users\Administrador\Desktop\CCL\Base de Referências\[área]\[matéria]\modelos-peca\`,
  nomeado pelo tipo de peça.
- Na ETAPA 8a, se a categoria "d" (modelo do caso) não vier preenchida,
  verifique se existe um modelo salvo para a matéria e o tipo de peça em
  elaboração antes de recorrer ao timbre genérico (ver regra em "Timbre
  padrão" acima).
- Se houver mais de um modelo salvo para o mesmo tipo de peça na mesma
  matéria, liste as opções ao usuário e pergunte qual usar, em vez de
  escolher sozinho.

**Orientações operacionais de sistema (Cálculo Jurídico/CJ, Tramitação
Inteligente), por matéria.** Cada subpasta de matéria pode ter um arquivo
`orientacoes-sistema.md`, com anotações de como operar o CJ ou a Tramitação
Inteligente para procedimentos específicos daquela matéria (ex.: "como fazer
um cálculo de revisão de benefício no CJ"). Diferente do resto da base, esse
conteúdo só nasce se o **usuário fornecer**, na pasta do caso, um documento
próprio de orientação sobre como operar um desses sistemas para aquele
benefício/procedimento — a skill nunca inventa nem infere esse fluxo sozinha.
- Quando a pasta do caso trouxer um documento desse tipo (guia, manual,
  passo a passo, print anotado, etc. sobre como operar o CJ/Tramitação
  Inteligente para a matéria em questão), leia-o e aplique as orientações
  no que for pertinente à peça em elaboração, e oriente o usuário
  ativamente, passo a passo, sobre como proceder com o cálculo/procedimento
  no sistema, com base no que o documento ensina.
- Ao final da Etapa 10 (mesmo fluxo de "Alimentando a base" abaixo), grave
  ou atualize `orientacoes-sistema.md` na subpasta da matéria com o que foi
  aprendido nesse caso sobre como operar o sistema para aquele
  benefício/procedimento — nunca sobrescrevendo uma orientação já salva sem
  necessidade, só acrescentando ou refinando.
- Em casos futuros da mesma matéria, se `orientacoes-sistema.md` já existir,
  consulte-o proativamente sempre que o caso envolver o mesmo tipo de
  cálculo/procedimento (ex.: outra revisão de benefício), e oriente o
  usuário com base nas anotações já salvas, sem precisar que ele reenvie o
  documento original.
- Esse conteúdo é estritamente operacional/interno (como usar o sistema),
  nunca a fonte de dados do caso em si, e nunca deve ser nomeado no corpo da
  peça protocolada (o sistema é ferramenta de trabalho do escritório, não
  fato do processo): use-o só para orientar o usuário e conferir o cálculo,
  nunca cite "CJ" ou "Tramitação Inteligente" no texto da minuta em si.

## Alimentando a base (triagem automática + uma única pergunta resumida)

Depois que o usuário aprovar a minuta final (ETAPA 10, opção 4), a própria
skill faz a triagem do que vale salvar, em vez de perguntar item por item —
tudo gravado diretamente em
`C:\Users\Administrador\Desktop\CCL\Base de Referências\`, nunca em
`referencias-escritorio/` (que fica só com timbre, orientações gerais e
regras comuns):

1. **Levante os candidatos.** Percorra o material desta peça e identifique,
   por tipo:
   - Trechos de lei/jurisprudência usados na fundamentação que tenham
     potencial de reaparecer em casos futuros da mesma matéria (descarte
     teses genéricas demais para virar entrada, ou hiperespecíficas demais
     para se repetir).
   - Parágrafos/pedidos redigidos nesta peça que sejam reutilizáveis (ex.:
     justiça gratuita, tutela de urgência) e ainda não estejam salvos.
   - A peça em si, como candidata a modelo, se for de um tipo/matéria sem
     modelo salvo ainda, ou uma versão sensivelmente melhor da que já existe.
   - Doutrina enviada nesta conversa, quando o usuário já a tiver enviado
     como material de embasamento (categoria "c") de forma que sugira valor
     de reuso, mesmo sem pedido explícito de "guardar".
   - Endereço de citação de órgão + comarca ainda não salvo em
     `enderecos-partes-re.md` (ver REGRAS DE QUALIFICAÇÃO DAS PARTES RÉS no
     SKILL.md).
   - Orientação de como operar o CJ/Tramitação Inteligente para a matéria,
     quando o usuário tiver fornecido esse tipo de documento na pasta do
     caso (ver "Orientações operacionais de sistema" acima) e ela ainda não
     estiver salva (ou estiver desatualizada) em `orientacoes-sistema.md`.
2. **Verifique duplicidade e pertinência antes de propor.** Para cada
   candidato de lei/jurisprudência ou parágrafo, confira o Índice do
   `base-conhecimento.md`/arquivo correspondente da matéria (ver
   `_MODELO-formato-base-conhecimento.md` e o README de
   `modelos-paragrafos/`, ambos na raiz da pasta local). Descarte
   silenciosamente, sem levar à pergunta, qualquer candidato que:
   - já tenha entrada equivalente na base (mesmo título/tema/tags), sem
     nuance nova a acrescentar; ou
   - seja específico demais deste caso concreto para ter valor de reuso
     (ex.: um dado de fato, não uma tese ou regra).
3. **Pergunta única, já pré-filtrada.** Apresente apenas o que sobrou do
   filtro acima, numa lista curta para aprovação de uma vez:
   > "Ao final desta peça, isto pode reforçar a base do escritório para
   > casos futuros:
   > 1. [título curto do trecho de lei/jurisprudência 1] → salvar em
   >    `Base de Referências\[área]\[matéria]\base-conhecimento.md`.
   > 2. [título curto do parágrafo/pedido] → salvar em
   >    `Base de Referências\modelos-paragrafos\` (ou na subpasta da
   >    matéria).
   > 3. Esta peça como modelo de [tipo de peça] para `[matéria]` (ainda não
   >    havia modelo salvo / esta versão é mais completa que a salva).
   > 4. [resumo curto da orientação de sistema aprendida] → salvar em
   >    `Base de Referências\[área]\[matéria]\orientacoes-sistema.md`.
   > Aprova salvar tudo, quer ajustar algum item, ou prefere não salvar
   > nada desta vez?"
   Se não houver nenhum candidato depois do filtro, não faça a pergunta —
   apenas informe rapidamente, em uma frase, que nada novo foi identificado
   para a base desta vez.
4. **Grave conforme aprovado**, seguindo sempre o formato estruturado do
   template (Índice + entrada, com título, tags, data e peça de origem):
   - Para leis/jurisprudência, **a citação completa exatamente como foi
     escrita na peça de origem** (tribunal/órgão, número do processo ou
     artigo, data de julgamento e a tese tal como redigida) — nunca um
     resumo ainda mais condensado do que já foi usado na peça. É a mesma
     citação abreviada e não literal já exigida pelas RESTRIÇÕES ABSOLUTAS,
     só preservada tal como redigida para reuso direto em peças futuras
     (ver `_MODELO-formato-base-conhecimento.md` na pasta local). Grave
     como nova entrada, ou atualize uma entrada existente com nuance nova
     (nunca duplicando o mesmo tema).
   - Para parágrafos/pedidos, o texto do trecho já com placeholders para os
     dados que mudam de caso para caso, seguindo o padrão do README de
     `Base de Referências\modelos-paragrafos\`.
   - Para a peça como modelo, o arquivo .docx final, renomeado para indicar
     claramente o tipo de peça; se já existir um arquivo do mesmo tipo,
     pergunte ao usuário se deve substituir ou manter os dois como variações
     (nomeando de forma a diferenciá-los) — só essa decisão específica exige
     pergunta à parte, por não caber no filtro automático de duplicidade.
   - Para endereço de citação, uma nova entrada em
     `enderecos-partes-re.md` com o órgão, a comarca/cidade e o endereço
     completo, seguindo o formato descrito naquele arquivo.
   - Para orientação de sistema (CJ/Tramitação Inteligente), o passo a passo
     aprendido em `orientacoes-sistema.md` da matéria, no mesmo nível de
     detalhe do documento que o usuário forneceu (não um resumo vago) —
     nova entrada por procedimento (ex.: "revisão de benefício"), ou
     atualização da existente se o caso novo trouxer um passo adicional ou
     uma correção.
Nunca grave nada sem passar pela pergunta única acima (mesmo pré-filtrada,
ela continua sendo a aprovação do usuário) e nunca sobrescreva uma entrada
existente sem necessidade — acrescente, ou atualize pontualmente quando a
entrada já existir e o caso novo trouxer nuance real. Essa gravação é sempre
uma edição direta de arquivo na pasta local do Windows — nunca inclua o
conteúdo desse banco de dados em commit, push ou qualquer alteração do
repositório da skill no GitHub.
