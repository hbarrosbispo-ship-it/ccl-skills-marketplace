# Formatação base do documento (peças e pareceres)

Regras de formatação compartilhadas por `pecas-previdenciarias-escritorio` e
`planejamento-previdenciario`. Cada skill mantém, no próprio SKILL.md ou em
sua própria referência, as regras de estrutura que só fazem sentido ali (ex.:
padrão de abertura/fechamento de peça, ordem de tópicos do corpo, ou a
estrutura fixa do parecer) — este arquivo cobre só fonte, espaçamento e o
padrão visual de tabelas, que são idênticos nas duas frentes.

## Fonte

- Fonte padrão do corpo do texto: Calibri, tamanho 12.
- Endereçamento/título do documento (o "Exmo. Sr. Dr. Juiz..." de uma peça,
  ou o título "PLANEJAMENTO PREVIDENCIÁRIO" de um parecer): Calibri, tamanho
  14.
- Citações longas de jurisprudência ou doutrina (ver
  `transcricao-jurisprudencia.md`): Calibri, tamanho 10, com recuo de 4 cm de
  parágrafo a partir da margem esquerda.
- Essas regras de fonte têm prioridade sobre qualquer fonte diferente que
  porventura apareça no modelo .docx enviado pelo usuário — o modelo define
  timbre e layout; a fonte e o tamanho seguem sempre este padrão do
  escritório, mesmo que o arquivo de modelo tenha sido criado ou editado com
  outra fonte por engano.

## Espaçamento e parágrafos

- Espaçamento de 1,5 entre linhas dentro dos parágrafos.
- Espaço de 12pt depois de cada parágrafo (`w:after`), além do espaçamento de
  1,5 entre linhas: configure isso como espaçamento "depois" do parágrafo na
  formatação, nunca como linha em branco manual digitada entre os
  parágrafos.
- Pule uma linha adicional (espaço extra "antes" do parágrafo, além do
  espaçamento padrão de 12pt) antes de cada tópico maior de numeração
  simples. Não pule linha adicional antes de subtópicos, que fluem
  normalmente só com o espaçamento padrão de 12pt.
- Parágrafos justificados, recuo de 1,25 cm no início de cada parágrafo e nos
  títulos de seção. Duas exceções universais a essa justificação: o bloco de
  assinatura final (nome dos advogados e OAB), que fica centralizado; e o
  título/nome do documento (nome da peça, ou "PLANEJAMENTO PREVIDENCIÁRIO"),
  que fica em negrito, maiúsculo e centralizado.
- Datas sempre no formato numérico (ex.: 20/10/2023), exceto as datas de
  abertura e fechamento do documento, que seguem a convenção formal e devem
  ser escritas por extenso (ex.: "Salvador/BA, 28 de julho de 2026.").
- **Parágrafos curtos.** Como regra geral, mantenha cada parágrafo em torno
  de, no máximo, 6 linhas. Ultrapassado esse limite, normalmente é sinal de
  que o parágrafo está tratando de mais de uma ideia e deve ser dividido.
  Aplique isso com parcimônia: o objetivo é evitar blocos de texto muito
  longos e difíceis de acompanhar, não dividir mecanicamente todo parágrafo
  que chegar a 6 linhas. Nunca divida um parágrafo só porque bateu no limite
  se a divisão não fizer sentido lógico (ex.: deixar o segundo parágrafo
  resultante com apenas uma linha, cortando o raciocínio no meio) — nesses
  casos, mantenha o parágrafo um pouco mais longo em vez de fragmentar
  artificialmente.
- Destaque em **negrito** pontual os principais pontos de cada parágrafo. O
  negrito não é para destacar um trecho aleatório: ele deve marcar o
  argumento principal do parágrafo, ou a frase que melhor resume do que
  aquele parágrafo realmente trata. Use com prioridade na frase de conclusão
  de cada tópico/subseção e nas principais partes argumentativas ao longo do
  texto. O uso deve ser comedido, restrito aos pontos de maior relevância,
  nunca negrito espalhado sem critério.

## Padrão visual de tabelas ("Quadros")

Sem exceções, quando o documento incluir alguma tabela:

- Fonte tamanho 10pt em todas as células, inclusive cabeçalho (mesmo com o
  corpo do texto em Calibri 12: tabela é a exceção documentada de tamanho).
- Cabeçalho com fundo cinza claro (`E7E6E6`) e texto em negrito.
- Bordas finas em cinza (`999999`), espessura mínima.
- Numeração sequencial simples ("Quadro 1", "Quadro 2"...), com legenda
  justificada (não centralizada) logo abaixo da tabela, citando o que o
  quadro mostra e a fonte dos dados.
- Nunca cite um "Quadro N" no texto antes de esse quadro já ter sido
  apresentado: revise a ordem de aparição sempre que uma tabela for movida
  ou uma nova for inserida.
