# Peça CCL

Plugin com a skill `peca-previdenciaria-tributaria`, usada pelo escritório para elaborar peças processuais e administrativas nas áreas previdenciária, tributária e cível.

## Como usar

Diga "peça", "peça CCL" ou "INICIAR" para começar o fluxo. A skill conduz, passo a passo, desde o recebimento dos documentos do caso até a redação da minuta final em .docx, com pausas de validação ao longo do processo.

Requer a skill `docx` (nativa) para a geração do arquivo final.

## Novidades na v0.4.0

- Verificação de vigência obrigatória antes de citar qualquer artigo,
  decreto, lei, IN, portaria ou súmula (nova exceção pontual em RESTRIÇÕES
  ABSOLUTAS + checagem nas Etapas 7, 9 e 10).
- Restrição geográfica de assinatura: Hélio só assina peças de processos
  tramitando na Bahia; fora dela, assina só o advogado da área aplicável.
- Espaçamento: 12pt depois de cada parágrafo (nativo do Word) + linha extra
  antes de tópicos maiores (não subtópicos).
- Justificação estendida a títulos de seção, endereçamento e legendas de
  figuras/quadros (exceções: bloco de assinatura e nome da peça, que ficam
  centralizados).
- "DOS PEDIDOS E REQUERIMENTOS" passa a ser tópico numerado na sequência da
  peça; lista de pedidos por letra maiúscula agora exige numeração nativa
  do Word (nunca "A." digitado); negrito no ponto principal de cada pedido;
  pedidos puramente descritivos (sem providência concreta) não entram mais
  na lista.

## Novidades na v0.3.0

- Nova pasta `referencias-escritorio/` empacotada junto com a skill:
  `modelo-timbre/` traz o timbre padrão do escritório (usado automaticamente
  quando o usuário não envia um modelo próprio no caso), e `civil/`,
  `previdenciario/` e `tributario/` reúnem trechos de lei e jurisprudência
  já validados por matéria, consultados na ETAPA 7. Ao final de cada peça
  aprovada, a skill pergunta se pode salvar ali os trechos mais relevantes
  usados, para reaproveitar em casos futuros.

## Novidades na v0.2.0

- Cabeçalho/endereçamento e nome do autor sempre em **negrito**.
- Seção final reordenada: título "DOS PEDIDOS E REQUERIMENTOS" primeiro, depois "Diante de todo o exposto, pleiteia-se:", com os itens numerados por **letras (A, B, C...)** em vez de tópicos genéricos.
- Inserção de prints dos documentos comprobatórios ao longo da minuta passa a ser **proativa por padrão**, com exceção de peças simples de patamar leve.
