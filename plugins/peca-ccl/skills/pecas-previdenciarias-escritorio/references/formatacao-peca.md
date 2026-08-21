# Estrutura e formatação específica da peça

Complementa `referencias-escritorio/regras-comuns/formatacao-base.md`
(fonte, espaçamento, tabelas — comum a peças e pareceres) com o que é
específico da estrutura de uma peça processual/administrativa.

## Padrão de abertura da peça

Toda peça judicial (petição inicial e demais peças que se dirigem a um
juízo) segue esta sequência fixa de abertura, nesta ordem, antes do primeiro
tópico numerado do corpo (ver "Ordem dos tópicos do corpo da peça" abaixo):

1. **Endereçamento.** "AO JUÍZO DO [vara/juizado/tribunal competente]..."
   (ou o destinatário equivalente do modelo do escritório), em negrito,
   justificado, Calibri 14 (ver `formatacao-base.md`).
2. **Caixa de prioridade, quando aplicável.** Se o caso tiver fundamento
   para tramitação prioritária (ex.: idoso, doença grave, pessoa com
   deficiência, gestante, nos termos da legislação aplicável), insira logo
   abaixo do endereçamento uma caixa de texto (ferramenta de desenho "caixa
   de texto" do Word, `w:txbxContent`, nunca uma tabela de uma célula só nem
   um parágrafo com borda de página inteira), com borda visível, contendo
   "Prioridade - [motivo(s), ex.: "Estatuto do Idoso e Doença Grave"]", em
   negrito. A caixa deve ser **compacta**, dimensionada para o tamanho do
   próprio texto (ajuste automático de largura/altura ao conteúdo, sem
   esticar até a margem direita da página) e alinhada à esquerda, replicando
   exatamente o padrão visual do modelo do escritório: nunca uma caixa que
   ocupe a largura inteira da página. Liste todos os motivos aplicáveis ao
   caso concreto na mesma caixa, separados por " e " ou vírgula. Se não
   houver fundamento para prioridade, omita essa caixa inteiramente, sem
   deixar espaço reservado vazio.
3. **Qualificação do autor.** Pule uma linha (espaço extra "antes" do
   parágrafo, além do espaçamento padrão de 12pt) entre a caixa de
   prioridade (ou, na ausência dela, o endereçamento) e o início deste
   parágrafo, mesmo padrão de espaçamento aplicado entre tópicos maiores
   (ver `formatacao-base.md`). Parágrafo justificado, com recuo de 1,25 cm,
   qualificando o autor (nome em negrito, nacionalidade, estado civil,
   profissão quando pertinente, CPF, RG, endereço com a citação de
   protocolo aplicável), encerrando com "vem, respeitosamente, por
   intermédio de seu procurador infra-assinado (doc. [N. procuração]), com
   fulcro no [dispositivo legal aplicável ao rito ou ao pedido principal],
   propor a presente".
4. **Nome da peça.** Centralizado, negrito, maiúsculo (ex.: "AÇÃO
   DECLARATÓRIA DE INEXISTÊNCIA DE RELAÇÃO JURÍDICO-TRIBUTÁRIA CUMULADA COM
   PEDIDO DE RESTITUIÇÃO DO INDÉBITO TRIBUTÁRIO"), conforme a exceção de
   centralização já prevista em `formatacao-base.md`.
5. **Qualificação da parte ré.** "em face de [RÉU]..." qualificando a parte
   ré (ver REGRAS DE QUALIFICAÇÃO DAS PARTES RÉS no SKILL.md), encerrando
   com "pelos fundamentos fáticos e jurídicos que passa a expor.".
6. A partir daqui começa o corpo numerado da peça, sempre iniciando pelo
   tópico "1. PRELIMINARMENTE" (ver "Ordem dos tópicos do corpo da peça"
   abaixo), mesmo quando não houver preliminar propriamente dita a levantar
   além da tramitação prioritária/justiça gratuita.

Esse padrão vale para petição inicial e demais peças dirigidas a um juízo.
Peças administrativas (requerimentos e recursos ao INSS) seguem o
endereçamento e a estrutura próprios do órgão, sem a caixa de prioridade
nem o "em face de" (que pressupõe parte ré judicial): mantenha, para essas
peças, a estrutura de abertura que já constar do modelo do escritório ou do
modelo enviado pelo usuário.

## Padrão de fechamento da peça

Toda peça judicial (petição inicial e demais peças dirigidas a um juízo)
segue esta sequência fixa de encerramento, logo após o último item da lista
de pedidos e requerimentos (ver espaçamento entre a lista e esta sequência
em "Dos Pedidos e Requerimentos" abaixo). Cada elemento abaixo é um
parágrafo próprio, nunca compactado com o seguinte: o espaçamento entre eles
segue o padrão geral de 12pt depois de cada parágrafo (ver
`formatacao-base.md`), nunca digite linhas em branco manuais para simular
esse espaço.

1. **Valor da causa**, quando aplicável ao rito. Parágrafo justificado, com
   recuo de 1,25 cm, no formato: "Dá-se à causa, para efeitos fiscais, o
   valor de R$ [valor] ([valor por extenso]), correspondente a [base do
   cálculo, ex.: "ao proveito econômico do pedido principal, com o
   reconhecimento de ambos os períodos tratados nos tópicos X e Y"],
   conforme [documento comprobatório, ex.: "memória de cálculo que instrui
   esta petição (Doc. N)"], sem prejuízo do arbitramento judicial do valor
   da causa, nos termos do art. 292, inciso [aplicável], do CPC.". Ajuste a
   base do cálculo e o documento de referência ao caso concreto; nunca deixe
   esse parágrafo genérico quando houver memória de cálculo ou planilha nos
   documentos do caso.
2. **"Nestes termos,"** — parágrafo próprio, apenas essa frase.
3. **"Pede deferimento."** — parágrafo próprio, apenas essa frase.
4. **Local e data por extenso**, parágrafo próprio (ex.: "Salvador/BA, 20
   de agosto de 2026."), conforme a exceção de data por extenso já prevista
   em `formatacao-base.md`.
5. **Bloco de assinatura**, centralizado (exceção à justificação padrão, já
   prevista em `formatacao-base.md`), com o(s) advogado(s) subscritor(es)
   definido(s) em `referencias-escritorio/regras-comuns/qualificacao-advogados.md`,
   respeitando a ordem de citação ali definida. Cada advogado ocupa duas
   linhas centralizadas: nome em **negrito e CAIXA ALTA** (nunca em
   minúsculo ou apenas capitalizado), seguido, na linha abaixo, do número da
   OAB. Quando houver mais de um subscritor, repita o par nome/OAB para cada
   um, na ordem definida.

Regras adicionais desse bloco:
- Mantenha o espaçamento padrão entre cada um desses elementos (valor da
  causa → "Nestes termos," → "Pede deferimento." → local e data → bloco de
  assinatura): nunca junte dois deles no mesmo parágrafo nem remova o
  espaço entre eles para economizar espaço na página.
- **Nunca inclua linha de assinatura** (traço/underline para assinatura
  manuscrita, ex. "_____________________") acima do nome do advogado: a
  peça é assinada eletronicamente, e o bloco de assinatura contém apenas o
  par nome (maiúsculo, negrito) / OAB, centralizados, sem qualquer marcação
  de linha para assinar.
- Se a peça não tiver valor de causa aplicável (ex.: peça administrativa, ou
  peça judicial incidental sem novo valor de causa a fixar), omita o item 1
  inteiramente e comece a sequência em "Nestes termos,".

## Fonte do marcador de lista

**Calibri é a única fonte do documento, sem exceção, inclusive na lista de
pedidos e requerimentos.** A lista numerada nativa do Word usada em "DOS
PEDIDOS E REQUERIMENTOS" (ver abaixo) às vezes herda uma fonte diferente da
usada no corpo do texto para o próprio marcador da lista (a letra maiúscula
gerada automaticamente pelo Word), por ser um elemento de formatação
separado do texto do parágrafo. Configure explicitamente a fonte do
marcador da lista (`w:rPr` dentro de `w:lvl`/`w:pPr` no XML de numeração)
como Calibri, no mesmo tamanho do corpo do texto (12), para que não sobre
nenhum trecho do documento em fonte diferente de Calibri.

## Ordem dos tópicos do corpo da peça

Fixa, salvo peça administrativa sem preliminar aplicável.

1. **PRELIMINARMENTE.** Sempre o primeiro tópico do corpo, em peça judicial
   (ver "Padrão de abertura da peça" acima). Reúne as preliminares
   propriamente ditas do caso (ex.: tramitação prioritária, justiça
   gratuita, e outras preliminares processuais aplicáveis, como
   incompetência, ilegitimidade ou prescrição, quando arguidas), cada uma
   em subtópico próprio (1.1, 1.2, ...). Não inclua aqui a tutela de
   urgência (ver regra própria abaixo) nem o mérito da causa.
2. **DOS FATOS.** Inicie com "Trata-se de ação visando o reconhecimento
   de...". Reconstrua o histórico fático com foco nas provas materiais,
   observando o mínimo de parágrafos do patamar aplicado
   (`calibragem-densidade.md`).
3. **DO DIREITO, por ponto controvertido.** Estrutura em três movimentos:
   norma ou doutrina da Etapa 7, depois cotejo com o fato concreto, depois
   conclusão favorável. Observe o mínimo de parágrafos por tese conforme o
   patamar aplicado. No administrativo, fundamente em Instruções Normativas
   e Decretos. No judicial, use também jurisprudência da doutrina.
4. **DA TUTELA DE URGÊNCIA, quando cabível.** Sempre o último tópico *de
   direito* do corpo, ou seja, o último tópico que desenvolve
   fundamentação/argumentação da causa: nunca misturado às preliminares nem
   disperso ao longo do mérito. Demonstre probabilidade do direito
   (remetendo objetivamente à fundamentação já exposta em "DO DIREITO", sem
   repeti-la por extenso) e perigo de dano ou risco ao resultado útil do
   processo, com base em dado concreto do caso (ex.: natureza alimentar do
   benefício, urgência médica, risco de dano irreparável). Se o caso não
   tiver pedido de tutela de urgência, omita esse tópico inteiramente, sem
   deixar espaço reservado vazio, e ajuste a numeração dos tópicos
   seguintes.
5. **Tópicos processuais de fechamento, quando existirem** (ex.: "DAS
   PUBLICAÇÕES" — requerimento genérico, sem nomear individualmente os
   advogados subscritores, ex.: "Requer-se que todas as publicações e
   intimações relativas ao presente feito sejam realizadas exclusivamente
   em nome dos advogados subscritores desta peça, sob pena de nulidade, nos
   termos do artigo 272, §5º, do Código de Processo Civil (CPC)." — isso
   evita erro de nome ou de ordem caso a composição de subscritores mude
   entre o rascunho e a versão final). Não são tópicos de direito/
   argumentação, e por isso podem vir depois da tutela de urgência,
   mantendo esta como o último tópico argumentativo da peça. Inclua apenas
   os que forem aplicáveis ao caso.
6. **DOS PEDIDOS E REQUERIMENTOS.** Sempre o último tópico da peça, depois
   de qualquer tópico processual de fechamento (ver regras específicas
   abaixo).

## Dos Pedidos e Requerimentos

- Inicie a seção com o título numerado "DOS PEDIDOS E REQUERIMENTOS"
  (continuando a sequência dos tópicos maiores da peça, ex.: se a peça tiver
  as seções 1, 2 e 3, essa seção é o tópico 4), seguido da frase "Diante de
  todo o exposto, pleiteia-se:".
- Liste os pedidos e requerimentos numerados por letras maiúsculas (A, B,
  C, D...), nunca por números: os tópicos e subtópicos do corpo da peça já
  usam algarismos arábicos, então a lista final de pedidos se diferencia
  visualmente usando letras. Escreva cada item com linguagem imperativa
  (PUGNA, POSTULA).
- Essa numeração por letras deve ser sempre gerada como lista numerada
  nativa do Word (`w:numPr`/`w:abstractNum` com `w:numFmt val="upperLetter"`),
  nunca como letra digitada manualmente no início do texto (ex.: nunca "A. "
  como caractere literal): isso garante que o Word reconheça e renumere a
  lista automaticamente se um item for inserido, movido ou removido depois.
- **A letra do marcador também é sempre em negrito.** Configure o negrito
  diretamente na definição do marcador da lista (`w:rPr` do nível de
  numeração), não apenas no texto do item: o negrito da letra é
  independente do negrito do trecho de destaque tratado no ponto abaixo, e
  vale mesmo nos itens em que nenhum trecho do texto for destacado.
- Dentro de cada item da lista, destaque em **negrito e em CAIXA ALTA** o
  ponto principal do pedido (a providência central requerida, ex.: "**o
  RECONHECIMENTO DA PRESCRIÇÃO INTERCORRENTE** da execução fiscal principal,
  consumada em 18/06/2024, com a extinção do feito, nos termos do art. 40,
  §4º, da LEF"), mantendo o restante do texto do item em formatação normal,
  sem caixa alta. A caixa alta acompanha exatamente a extensão do trecho em
  negrito, nunca mais nem menos que ele.
- Não cite, dentro de um pedido, um dispositivo, percentual ou fator
  numérico específico (ex.: um fator de conversão) cuja base legal não
  esteja vigente ou não tenha sido explicada na fundamentação do item
  correspondente (ver regra de citação de fontes). Nesses casos, formule o
  pedido de forma genérica (ex.: "conversão em tempo comum", sem fixar o
  fator), deixando o dimensionamento a cargo do órgão julgador.
- Inclua citações e intimações, proveito econômico (DIP, parcelas,
  correção), gratuidade da justiça, produção de provas e valor da causa.
- **Honorários advocatícios.** Antes de incluir o pedido de condenação em
  honorários de sucumbência, verifique a orientação geral sobre honorários
  em JEF em `referencias-escritorio/orientacoes-gerais.md`: como regra
  geral, não são devidos honorários de sucumbência em primeiro grau nos
  Juizados Especiais Federais, salvo em peça recursal.
- Não inclua pedido ou tese não aprovada nas Etapas 5/6 sem antes perguntar
  ao usuário.
- Evite pedidos puramente descritivos, sem efeito prático sobre o processo
  (ex.: "seja o Autor cientificado de X", "tome-se ciência de Y"). Um pedido
  só deve constar da lista se corresponder a uma providência concreta
  requerida ao juízo (declarar, determinar, condenar, autorizar, intimar,
  reconhecer e afins). Fatos que mereçam registro, mas sem pedido de
  providência associado, ficam no corpo da peça (Dos Fatos/Do Direito), não
  na lista final de pedidos.
- Entre o último item da lista de pedidos e a sequência de fechamento (valor
  da causa, "Nestes termos,", "Pede deferimento.", local/data e bloco de
  assinatura), pule uma linha (espaço extra "antes" do primeiro parágrafo de
  fechamento, além do espaçamento padrão de 12pt), no mesmo padrão aplicado
  entre tópicos maiores.

## Verificação pré-emissão (monólogo interno)

> "O pedido final é consequência lógica direta de todos os argumentos
> expostos?" Se não, revise antes de gerar a saída.
> "Todo artigo, decreto, lei, instrução normativa, portaria ou súmula
> citado na peça teve sua vigência verificada?" Se não, verifique antes de
> gerar a saída.
