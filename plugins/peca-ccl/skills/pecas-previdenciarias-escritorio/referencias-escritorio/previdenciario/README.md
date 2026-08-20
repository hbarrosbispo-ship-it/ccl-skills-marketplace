# Base de Referências — Previdenciário

Cada matéria/benefício previdenciário tem sua própria subpasta aqui (ex.:
`auxilio-doenca/`, `loas/`, `aposentadoria-por-invalidez/`,
`aposentadoria-por-tempo-de-contribuicao/`), criada sob demanda na primeira
vez que o escritório trabalha aquela matéria. Não crie subpastas
antecipadamente para matérias que ainda não surgiram em nenhum caso.

Cada subpasta de matéria pode conter:

- `base-conhecimento.md` — lei, jurisprudência e direcionamentos gerais já
  validados, no formato definido em
  `_referencias-escritorio/_TEMPLATE-base-conhecimento.md` (um nível acima).
- `doutrina/` — arquivos originais de doutrina (PDF/Word) já enviados pelo
  usuário e guardados para consulta futura.
- `modelos-peca/` — peças .docx já elaboradas e aprovadas, para reutilizar
  como ponto de partida em casos futuros do mesmo tipo.
- `modelos-paragrafos/` — parágrafos/pedidos específicos dessa matéria (mais
  específicos que os genéricos em `_referencias-escritorio/modelos-paragrafos/`).

Essa pasta é usada pelas skills `pecas-previdenciarias-escritorio` e
`planejamento-previdenciario` — ver a seção "BASE DE REFERÊNCIAS DO
ESCRITÓRIO" em cada uma delas para o fluxo completo de consulta e
alimentação.
