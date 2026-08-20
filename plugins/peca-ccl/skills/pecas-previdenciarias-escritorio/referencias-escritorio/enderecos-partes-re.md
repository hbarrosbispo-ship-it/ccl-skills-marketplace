# Endereços de Citação — Partes Rés

Endereços de citação já confirmados em peças anteriores, por órgão/parte ré
e por comarca/seção judiciária, para reutilizar sem precisar perguntar de
novo toda vez que a mesma parte ré for citada na mesma cidade. Compartilhado
entre as skills `pecas-previdenciarias-escritorio` e (quando aplicável)
`planejamento-previdenciario`.

## Índice
<!-- ex.: - INSS — Salvador/BA
     - INSS — Feira de Santana/BA
     - União Federal (PGFN) — Salvador/BA -->

---

<!--
Formato de cada entrada:

## [ÓRGÃO/PARTE RÉ] — [Cidade/UF ou Seção Judiciária]
**Adicionado em:** DD/MM/AAAA — peça de origem: [tipo de peça + caso, sem
dado sensível desnecessário]

Endereço completo de citação, no formato usado na qualificação da parte ré
(logradouro, número, bairro, cidade, UF, CEP).
-->

## Como a skill usa este arquivo

- Na ETAPA 8a/ETAPA 9 (REGRAS DE QUALIFICAÇÃO DAS PARTES RÉS), antes de
  marcar o endereço da parte ré como "[a preencher]", verifique o Índice
  deste arquivo pelo par órgão + comarca/cidade onde a peça tramita (ex.:
  "INSS — Salvador/BA"). Se existir entrada, use o endereço salvo
  diretamente, sem perguntar de novo, e informe ao usuário que o endereço
  veio da base salva (permitindo correção pontual se algo mudou).
- Se não existir entrada para aquele órgão + comarca, siga a regra normal
  (endereço do material do caso, ou "[a preencher]" com alerta ao usuário).
- Quando um endereço novo for confirmado (pelo material do caso ou pelo
  usuário) para um órgão + comarca que ainda não consta aqui, ele entra
  como candidato na triagem final de "Alimentando a base" (ver BASE DE
  REFERÊNCIAS DO ESCRITÓRIO na skill de peças), junto com os demais itens
  daquela pergunta única resumida — nunca grava sem passar por ela.
- Nunca sobrescreva uma entrada existente sem confirmação; se o endereço de
  um órgão mudar (ex.: mudança de sede), pergunte ao usuário se deve
  atualizar a entrada existente ou manter as duas (a antiga marcada como
  desatualizada).
