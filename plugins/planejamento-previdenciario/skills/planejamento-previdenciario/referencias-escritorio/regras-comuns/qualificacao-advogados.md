# Regras de qualificação de advogados (peças e pareceres)

Regra base compartilhada por `pecas-previdenciarias-escritorio` e
`planejamento-previdenciario`.

- Sempre incluir como subscritor HÉLIO BARROS BISPO DOS SANTOS, OAB/BA
  90.527, exceto na situação prevista abaixo sobre a restrição geográfica.
- Se o documento for da área tributária ou cível, incluir também CAIO CESAR
  BAHIA CAMPOS, OAB/BA 55.976.
- Se o documento for da área previdenciária, incluir também AMAN ALMEIDA DA
  COSTA PINHEIRO, OAB/BA 54.487.
- **Ordem de citação dos subscritores.** Em qualquer trecho que liste os
  advogados subscritores (bloco de assinatura, qualificação do autor "por
  seu(s) procurador(es)", ou qualquer outra menção), cite primeiro Caio Cesar
  Bahia Campos ou Aman Almeida da Costa Pinheiro (o que for aplicável à área)
  e Hélio Barros Bispo dos Santos por último, quando ele também subscrever.

## Restrição geográfica de Hélio (só peças processuais e administrativas)

Hélio só assina peças de processos que tramitam no estado da Bahia. Em
processos de outros estados, não inclua a assinatura de Hélio: ele possui
inscrição apenas na OAB/BA, e a OAB exige inscrição suplementar para atuação
habitual (a partir de 5 processos) em outra seccional. Nesses casos, a peça é
subscrita apenas pelo(s) advogado(s) da área aplicável.

Essa restrição vale para a skill `pecas-previdenciarias-escritorio`
(petições, requerimentos, recursos) — identifique o estado de tramitação a
partir do foro/comarca/vara/seção judiciária indicados nos documentos antes
de definir os subscritores.

**Não se aplica** ao parecer de planejamento previdenciário
(`planejamento-previdenciario`): o parecer é um documento consultivo entregue
diretamente ao cliente, sem protocolo em juízo ou órgão, logo não há
"tramitação" em uma seccional específica. Se o planejamento indicar que o
cliente pretende ajuizar ação fora da Bahia com base na estratégia
recomendada, sinalize esse ponto ao usuário para que ele avalie a composição
de subscritores na peça processual correspondente, quando ela for elaborada.
