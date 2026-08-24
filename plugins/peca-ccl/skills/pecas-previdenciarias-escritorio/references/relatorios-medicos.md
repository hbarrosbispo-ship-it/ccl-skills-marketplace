# Análise de prova médica e pericial (benefício por incapacidade)

Aplica-se sempre que o caso envolver pedido de benefício por incapacidade
(auxílio-doença/incapacidade temporária, aposentadoria por invalidez/
incapacidade permanente, BPC-LOAS por incapacidade e afins), tanto na via
administrativa quanto na judicial. Cobre dois tipos de documento, com
tratamento diferente: (1) relatórios/laudos médicos apresentados pelo
próprio segurado como prova, e (2) perícias administrativas (INSS) ou
judiciais já realizadas no caso, que também são fonte de prova e não devem
ser lidas só pela conclusão final.

## 1. Checklist formal do relatório/laudo apresentado pelo segurado

O INSS pode negar seguimento a um pedido, por vício formal, quando o
relatório ou laudo médico/odontológico apresentado como prova da
incapacidade não preenche os requisitos mínimos exigidos. Por isso, ao
analisar cada relatório/laudo da categoria "e" (Etapa 3 do SKILL.md),
verifique expressamente se ele atende a todos os itens abaixo:

1. Documentação legível e sem rasuras.
2. Identificação do paciente.
3. Data de emissão.
4. Diagnóstico ou código da Classificação Internacional de Doenças (CID).
5. Assinatura do profissional, que pode ser eletrônica, desde que passível
   de validação.
6. Identificação do profissional, com nome e registro no CRM, CRO ou RMS,
   ou carimbo (ver REGRAS DE CITAÇÃO DE PROFISSIONAIS MÉDICOS no SKILL.md
   sobre qual CRM citar na peça).
7. Identificação do período de afastamento. Se a incapacidade for
   definitiva, o relatório deve constar como "afastamento por tempo
   indeterminado" (não uma data específica de retorno).

Se algum item estiver ausente ou não puder ser confirmado no documento,
sinalize ao usuário, por documento, exatamente qual(is) requisito(s)
está(ão) faltando e o risco de indeferimento por vício formal, e pergunte:
> 1. Vou providenciar um relatório complementar ou corrigido.
> 2. Prosseguir mesmo assim, ciente do risco de indeferimento por
>    formalidade.

Essa verificação formal não substitui a leitura de mérito do conteúdo do
relatório (gravidade do quadro, nexo com a atividade laboral, prognóstico
etc.) nem a regra de **Alerta obrigatório de fato desfavorável em
documento** (ver RESTRIÇÕES ABSOLUTAS no SKILL.md): leia a descrição
completa do relatório, e não apenas os trechos favoráveis à tese do
cliente.

## 2. Perícias administrativas e judiciais como fonte de prova, mesmo quando o resultado geral é desfavorável

O checklist acima é sobre documentos que o próprio segurado apresenta como
prova. Mas o caso também costuma trazer **perícias já realizadas** —
laudo de perícia médica administrativa do INSS (inclusive de um pedido
anterior, ainda que indeferido) ou perícia judicial em processo relacionado.
Essas perícias são sempre categoria "b" ou "e" da pasta do caso, e devem ser
lidas por inteiro na Etapa 3, com a mesma atenção dada aos laudos do
segurado — **nunca só pela conclusão/resultado final registrado no
documento** ("Concluído com Sucesso", "Indeferido", "Não configurada
incapacidade" etc.).

**Por quê isso importa.** Uma perícia pode negar exatamente o benefício que
motivou o exame e, ainda assim, registrar em campos técnicos objetivos
(indicadores, CID, limitações funcionais, prazo estimado) uma constatação
favorável a uma tese diferente. Exemplo real: uma perícia médica do INSS
para BPC/LOAS foi concluída com o resultado "indeferido" quanto ao benefício
então pleiteado, mas o campo "Indicador de Impedimento de Longo Prazo"
constava como "Sim" — exatamente o requisito técnico central do art. 20,
§2º, da Lei 8.742/93 (LOAS), com a redação da Lei 13.982/2020. Ignorar esse
campo só porque o resultado geral da perícia foi negativo desperdiçaria a
prova mais forte disponível no caso.

**Como proceder:**
- Ao ler qualquer perícia (administrativa ou judicial), extraia **todos os
  campos e indicadores técnicos registrados**, não só o resultado/situação
  final. Tabelas de resultado de perícia do INSS costumam trazer, além da
  situação, campos como CID, indicador de impedimento de longo prazo,
  indicador de deficiência, data de início da incapacidade, e observações
  do perito — leia cada um.
- Se algum desses campos for objetivamente favorável a uma tese diferente
  da que a perícia analisou (ex.: impedimento de longo prazo constatado
  numa perícia de auxílio-doença, útil para uma futura tese de BPC-LOAS; ou
  incapacidade parcial constatada numa perícia que negou incapacidade
  total, útil para uma tese de aposentadoria por invalidez), **destaque
  esse dado ao usuário explicitamente** e avalie se ele sustenta o pedido
  em elaboração, mesmo vindo de um documento cujo resultado final foi
  desfavorável.
- Isso não dispensa a regra de **Alerta obrigatório de fato desfavorável em
  documento** (RESTRIÇÕES ABSOLUTAS no SKILL.md) — as duas leituras
  coexistem: leia o documento inteiro tanto para não perder um dado
  favorável relevante escondido atrás de uma conclusão negativa, quanto
  para não esconder um dado desfavorável relevante escondido atrás de uma
  conclusão aparentemente positiva.

## 3. Atividade laboral do segurado durante o período alegado de incapacidade

O fato de o segurado estar trabalhando durante o período em análise **não
tem o mesmo peso em todo tipo de benefício por incapacidade** — não trate
isso como sempre desfavorável, nem sempre neutro. Avalie conforme o
benefício:

- **Auxílio-doença/incapacidade temporária.** Estar trabalhando **não
  reduz, por si só, as chances de o benefício ser concedido**. O segurado
  pode estar exercendo a atividade mesmo incapacitado ou doente, muitas
  vezes por necessidade econômica de sustento próprio ou da família,
  justamente na ausência do benefício que está sendo pleiteado. Isso não
  afasta a incapacidade comprovada por laudo/perícia. Não presuma
  automaticamente, e não deixe a peça sugerir, que o exercício de atividade
  enfraquece a tese de incapacidade nessa hipótese — avalie o quadro
  clínico e a eventual incompatibilidade entre a atividade exercida e a
  limitação, sem presunção contrária ao segurado só pelo fato de haver
  trabalho registrado.
- **BPC-LOAS (benefício assistencial por deficiência).** Aqui a lógica é
  diferente: o requisito de "impedimento de longo prazo" pressupõe, por
  definição legal (art. 20, §2º, da LOAS), uma barreira que, em interação
  com fatores diversos, pode obstruir a participação plena e efetiva da
  pessoa na sociedade em igualdade de condições, o que inclui a vida
  laboral. Constatar que a pessoa está efetivamente trabalhando **tende a
  ser desfavorável** à tese de impedimento de longo prazo, e deve ser
  tratado com a cautela da regra de **Alerta obrigatório de fato
  desfavorável em documento**. Avalie, ainda assim, se a atividade é
  residual, protegida, ou incompatível com a alegação antes de presumir que
  ela é definitivamente contraditória ao pedido.

Confirmado pelo usuário em 2026-08-24, depois de uma sessão anterior ter
tratado "o segurado está trabalhando" como fato genericamente desfavorável
mesmo num caso de auxílio-doença, quando deveria ter sido tratado como
neutro/possivelmente favorável (compatível com incapacidade parcial ou com
necessidade de sustento) — a distinção entre os dois benefícios acima é a
correção desse erro.
