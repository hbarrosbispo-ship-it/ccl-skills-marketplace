# Transcrição de jurisprudência (exceção controlada)

Regra compartilhada por `pecas-previdenciarias-escritorio` e
`planejamento-previdenciario`. Por padrão, jurisprudência nunca é transcrita
literalmente (ver RESTRIÇÕES ABSOLUTAS de cada skill) — mencione apenas a
tese relevante, contextualizada ao caso/cliente. Essa regra pode ser
excepcionada apenas quando **todas** as condições abaixo estiverem presentes.

## Condições

1. Existe um documento de pesquisa de jurisprudência para o caso, e a
   transcrição é extraída **exclusivamente** dele, nunca de memória. Esse
   documento pode ter duas origens:
   a. Fornecido pelo usuário na pasta do caso (ex.: um PDF reunindo ementas
      pesquisadas por ele).
   b. Gerado pela própria skill `pecas-previdenciarias-escritorio` via
      pesquisa no Jus IA, sob pedido expresso do usuário (ver
      `references/pesquisa-jurisprudencia-jusia.md` daquela skill). Só conta
      como origem válida o `.md` gerado por esse procedimento, com as ementas
      já conferidas na fonte.
2. **Autenticidade presumida por nome.** Qualquer documento cujo nome de
   arquivo ou de pasta remeta a "jurisprudência(s)" (ou variação óbvia, como
   "jurisprudencias", "pesquisa de jurisprudencia", "julgados") é presumido
   autêntico e transcritível integralmente, sem precisar perguntar ao
   usuário. Só pergunte explicitamente sobre autenticidade quando o
   documento de pesquisa não tiver nenhuma indicação de nome nesse sentido
   (ex.: um PDF avulso, sem nome claro, misturado a outros materiais).

## Como transcrever, presentes as condições

- **Não substitua a transcrição pela simples citação do número do
  processo.** Transcrever integralmente significa reproduzir o texto da
  ementa, nunca apenas mencionar o tribunal e o número de vários julgados em
  uma frase corrida. Escolha o(s) julgado(s) mais relevante(s) do documento
  de pesquisa para o ponto em discussão e transcreva a ementa por inteiro.
- Formate como citação direta longa, conforme a ABNT NBR 10520: recuo de
  4 cm a partir da margem esquerda, fonte tamanho 10, espaçamento simples
  (1,0), sem aspas.
- **Negrito obrigatório na transcrição.** Toda ementa transcrita deve conter
  um trecho em **negrito**, sem exceção. O trecho destacado deve ser sempre a
  parte mais importante da ementa para o argumento em discussão, nunca um
  destaque aleatório ou secundário.
- Ao introduzir a transcrição, se o julgado for de tribunal diverso daquele
  em que o processo tramita (peça) ou do foro habitual do cliente
  (planejamento), prefira uma frase introdutória genérica, como "É o que
  também reconhece a jurisprudência:", em vez de nomear o tribunal específico
  na frase. Quando o julgado transcrito for do próprio tribunal/órgão
  competente, pode nomeá-lo normalmente na frase introdutória.
- É permitido omitir trechos menos úteis da ementa, marcando a supressão com
  "(...)".
- Identifique a fonte (tribunal, número do processo, órgão julgador, relator
  quando identificável com segurança, data de publicação) em **nota de
  rodapé real do Word** ao final da citação, não como linha de texto no
  corpo do documento.
- Nunca infira ou complete um dado da decisão (como o nome do relator) que
  não conste de forma inequívoca no documento de pesquisa. Prefira omitir o
  dado a arriscar um erro.
- Fora dessas condições, volta a valer a regra padrão: mencionar apenas a
  tese, sem transcrição literal.
