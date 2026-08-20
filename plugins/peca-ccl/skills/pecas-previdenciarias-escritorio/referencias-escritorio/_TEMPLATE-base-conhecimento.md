# Modelo de arquivo `base-conhecimento.md` (por matéria)

Este é o modelo que `previdenciario/[matéria]/base-conhecimento.md`,
`tributario/[matéria]/base-conhecimento.md` e
`civil/[matéria]/base-conhecimento.md` devem seguir. Reúne lei, jurisprudência
e direcionamentos gerais já validados em peças e planejamentos anteriores
daquela matéria específica — é o "banco de dados" que as skills
`pecas-previdenciarias-escritorio` e `planejamento-previdenciario` alimentam
ao final de cada peça/planejamento (ver seção "Alimentando a base" em cada
skill) e consultam no início da próxima.

## Por que essa estrutura existe

Duas coisas precisam ser rápidas conforme a base cresce:
1. **Checar duplicidade** antes de acrescentar uma entrada nova — sem reler o
   arquivo inteiro toda vez.
2. **Encontrar a entrada certa** na hora de redigir uma peça nova.

Por isso todo arquivo `base-conhecimento.md` tem um Índice no topo (título +
tags de cada entrada) e entradas padronizadas abaixo. Ao decidir se algo é
"pertinente e não repetido", a skill compara **primeiro contra o Índice**
(título e tags), não contra o texto completo de cada entrada.

## Estrutura do arquivo

```markdown
# Base de Conhecimento — [Matéria] (ex.: Auxílio-Doença)

## Índice
- [Título curto da entrada 1] — tags: tag-a, tag-b
- [Título curto da entrada 2] — tags: tag-a, tag-c

---

## [Título curto da entrada 1]
**Tags:** tag-a, tag-b
**Tipo:** lei | jurisprudência | tese/direcionamento
**Adicionado em:** DD/MM/AAAA — peça de origem: [tipo de peça + cliente/caso, sem dado sensível desnecessário]

[Resumo objetivo: dispositivo (Lei/artigo) ou julgado (tribunal, número,
tese), e uma nota curta de contexto explicando quando/como essa entrada se
aplica. Nunca o texto integral do julgado ou da lei — só o resumo, no mesmo
padrão de citação abreviada usado nas peças.]

---

## [Título curto da entrada 2]
...
```

## Regras de uso

- **Título curto e específico.** Não use títulos genéricos como "Jurisprudência
  sobre incapacidade" — use algo que já diferencie a tese, ex.: "STJ afasta
  exigência de início de prova material contemporânea ao fato gerador
  (Tema XXX)". Um título específico é o que torna a checagem de duplicidade
  no Índice confiável.
- **Tags consistentes.** Reaproveite tags já usadas no Índice em vez de criar
  sinônimos (ex.: sempre "auxilio-doenca", nunca alternar com
  "auxílio doença" ou "beneficio-por-incapacidade" para a mesma coisa).
- **Checagem de duplicidade, passo a passo:**
  1. Leia o Índice do arquivo da matéria (não precisa ler as entradas
     inteiras).
  2. Se já existir uma entrada com o mesmo título, tema ou tags
     equivalentes, **não crie uma nova entrada** — em vez disso, avalie se a
     entrada existente já cobre o ponto (nesse caso, não faz nada) ou se o
     caso novo traz um ângulo/nuance adicional que vale a pena incorporar
     (nesse caso, atualize a entrada existente, acrescentando a nuance,
     sem apagar o que já estava lá).
  3. Só crie uma entrada nova quando o tema não tiver equivalente no
     Índice.
- **Nunca sobrescreva sem necessidade.** Acrescentar (nova entrada ou
  atualização pontual de uma existente) é o padrão; substituir o conteúdo de
  uma entrada inteira só quando a informação antiga estiver desatualizada ou
  incorreta (ex.: dispositivo revogado).
- Ao criar a primeira entrada de uma matéria nova, crie também o Índice,
  mesmo com um único item.
