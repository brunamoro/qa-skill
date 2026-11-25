# qa-skills

Skills do Claude Code para QA.

## gerar-casos-de-teste

Gera casos de teste (positivos, negativos e de limite) em tabela, atuando como analista de QA sênior. O padrão é o Cadastro do BugBank.

Uso:

- `/gerar-casos-de-teste` usa os requisitos do Cadastro do BugBank.
- `/gerar-casos-de-teste <funcionalidade e requisitos>` usa outra funcionalidade.

Para usar em qualquer projeto, copie as pastas de `.claude/skills/` para `~/.claude/skills/`.

## revisar-casos-de-teste

Faz a IA questionar o próprio resultado: aponta requisitos ambíguos ou incompletos, cenários não cobertos e os maiores riscos para o usuário e para o negócio. Quando falta informação, lista como dúvida para o time de produto.

Uso: rode `/revisar-casos-de-teste` logo depois de `/gerar-casos-de-teste`, na mesma conversa.

## validar-casos-de-teste

Auditoria independente dos casos de teste gerados por IA, como QA Sênior (ISTQB CTFL v4.0.1 e CT-GenAI v1.1). Avalia cada caso em seis lentes (aderência, cobertura, dados e limites, risco, executabilidade, rastreabilidade) com notas de 0 a 2, classifica em aprovado, aprovado com ressalvas, reprovado ou pendente de esclarecimento e entrega resumo executivo, matriz de avaliação, análise detalhada, lacunas de cobertura e plano de ação P0–P3.

Uso: rode `/validar-casos-de-teste` depois de `/gerar-casos-de-teste`, na mesma conversa, ou passe requisitos e casos como argumento.

## refinar-user-story

Refinamento crítico de User Stories como especialista em Business Analysis, Product Ownership, Engenharia de Requisitos e QA (ISTQB CTFL v4.0.1). Avalia a história em seis lentes e pelo INVEST, gera perguntas priorizadas (P0–P3) para o Product Owner, monta a matriz de rastreabilidade e dá o parecer final de prontidão.

Uso: `/refinar-user-story <User Story com critérios de aceite>`. Recomendado antes de `/gerar-casos-de-teste`.
