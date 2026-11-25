---
name: revisar-casos-de-teste
description: Faz a IA questionar os casos de teste que ela mesma gerou, apontando requisitos ambíguos ou incompletos, cenários não cobertos e riscos para o usuário e para o negócio. Use depois de gerar casos de teste (por exemplo, com /gerar-casos-de-teste) ou quando o usuário pedir para revisar, criticar ou questionar casos de teste.
---

# Revisar casos de teste

Use os requisitos e os casos de teste que já estão na conversa. Se o usuário passou outros requisitos ou casos como argumento ($ARGUMENTS), analise esses. Se não houver requisitos nem casos de teste na conversa, peça ao usuário antes de continuar.

Siga o prompt abaixo à risca.

---

Agora analise os requisitos e os casos que você gerou e responda:

1. Quais pontos do requisito estão ambíguos ou incompletos?
2. Quais cenários você NÃO cobriu e que poderiam revelar falhas?
3. Quais são os maiores riscos dessa funcionalidade para o usuário e para o negócio?

Não invente regras: quando faltar informação, aponte como dúvida para o time de produto.
