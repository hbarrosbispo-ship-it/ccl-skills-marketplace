# CCL Skills Marketplace

Marketplace privado de plugins do escritório para o Claude Code / Cowork.

## Plugins

- **peca-ccl** — elaboração de peças processuais e administrativas
  previdenciárias, tributárias e cíveis.
- **planejamento-previdenciario** — parecer de planejamento previdenciário
  entregue ao cliente.

## Como instalar (Cowork)

Diretório → Plugins → "+" → Adicionar marketplace → Adicionar de um
repositório → cole a URL deste repositório.

## Como instalar (Claude Code)

```
/plugin marketplace add <url-deste-repositorio>
/plugin install peca-ccl@escritorio-ccl
/plugin install planejamento-previdenciario@escritorio-ccl
```

## Atualizando

Depois de editar uma skill (normalmente em `~/.claude/skills/`), sincronize
o conteúdo para dentro de `plugins/<nome>/skills/...` neste repositório,
faça commit e push. No Cowork/Claude Code, sincronize o marketplace
(`/plugin marketplace update` ou o botão equivalente no Cowork) para puxar
a versão nova — sem precisar trocar arquivo `.plugin` manualmente.

Cada plugin carrega sua própria cópia de `referencias-escritorio/`
(timbre do escritório e trechos de lei/jurisprudência validados por
matéria) — plugins não compartilham arquivos entre si depois de instalados,
então essa pasta é replicada dentro de cada plugin.
