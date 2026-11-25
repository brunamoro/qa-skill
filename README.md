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
