# Planejamento Previdenciário

Plugin com a skill `planejamento-previdenciario`, para elaborar o parecer/estudo de planejamento previdenciário entregue ao cliente (Consulente).

## Como usar

Peça para "montar/elaborar o planejamento previdenciário" ou "estudo de aposentadoria" de um cliente. Diferente da skill `peca-ccl`, este documento é consultivo, endereçado ao próprio cliente, em linguagem acessível.

Requer a skill `docx` (nativa) para a geração do arquivo final.

## Novidades na v0.4.0

- Nova seção REGRAS DE CITAÇÃO DE FONTES, com verificação de vigência
  obrigatória antes de citar qualquer dispositivo (checada nas Etapas 5 e
  6), e a mesma exceção controlada de transcrição integral de
  jurisprudência das peças processuais.
- Esclarecido que a restrição geográfica de Hélio (só assina peças da
  Bahia) não se aplica ao planejamento — parecer consultivo, sem
  tramitação em juízo.
- Espaçamento: 12pt depois de cada parágrafo (nativo do Word) + linha extra
  antes dos tópicos maiores (1., 2., 3.), não das subseções.
- Legendas de imagens e de quadros passam a ser justificadas, não
  centralizadas.

## Novidades na v0.3.0

- Nova pasta `referencias-escritorio/` empacotada junto com a skill,
  compartilhada com a `peca-ccl`: `modelo-timbre/` traz o timbre padrão do
  escritório (usado quando o usuário não envia modelo próprio) e
  `previdenciario/` reúne trechos de lei/jurisprudência já validados por
  matéria. Uso deliberadamente parcimonioso aqui — só como checagem técnica
  de bastidor, nunca citação extensa no parecer, já que o público é o
  cliente leigo. Ao final de cada parecer aprovado, a skill pergunta se pode
  salvar os trechos mais relevantes usados.

## Novidades na v0.2.0

- Cabeçalho e nome do Consulente sempre em **negrito**, alinhado com a mesma regra da skill `peca-ccl`.
- Inserção de prints dos documentos mais relevantes (CNIS, relatórios de cálculo, contracheques) ao longo do parecer passa a ser **proativa por padrão**, com exceção de planejamentos muito simples.
- (Sem mudança na estrutura de pedidos — o parecer não tem seção de pedidos/requerimentos, por não ser dirigido a um juízo.)
