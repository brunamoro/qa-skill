---
name: gerar-casos-de-teste
description: Gera casos de teste (positivos, negativos e de limite) em tabela, atuando como analista de QA sênior. Use quando o usuário pedir para gerar/criar casos de teste, cenários de teste ou plano de testes, em especial para o Cadastro do BugBank. Aceita requisitos de outra funcionalidade como argumento.
---

# Gerar casos de teste

Siga o prompt abaixo à risca.

Se o usuário passou argumentos ($ARGUMENTS) com outra funcionalidade ou outros requisitos, troque as seções CONTEXTO e REQUISITOS pelo que ele informou e mantenha TAREFA, REGRAS e FORMATO. Sem argumentos, use o contexto e os requisitos do Cadastro do BugBank abaixo.

---

Atue como um analista de QA sênior, com experiência em testes de aplicações web financeiras.

## CONTEXTO
Estou testando a funcionalidade de Cadastro do BugBank, um banco digital fictício usado para prática de testes. Abaixo estão os requisitos da funcionalidade.

## REQUISITOS
- Os campos Nome, Email, Senha e Confirmação de senha são de preenchimento obrigatório
- Tentativa de cadastro sem preencher nome deve visualizar a mensagem "Nome não pode ser vazio"
- Tentativa de cadastro sem preencher email deve visualizar a mensagem "Email não pode ser vazio"
- Tentativa de cadastro sem preencher senha deve visualizar a mensagem "Senha não pode ser vazio"
- Tentativa de cadastro sem preencher confirmação de senha deve visualizar a mensagem "Confirmar senha não pode ser vazio"
- Deixar ativo a opção "Criar conta com saldo" deve criar conta com saldo de R$ 1.000,00
- Deixar inativo a opção "Criar conta com saldo" deve criar conta com saldo de R$ 0,00
- Senha e confirmação de senha precisam ser iguais
- Cadastrar conta com sucesso deve exibir número da conta criada

## TAREFA
Gere casos de teste para essa funcionalidade, cobrindo cenários positivos, negativos e de limite.

## REGRAS
- Baseie-se somente nos requisitos acima. Não invente regras de negócio que não estejam descritas.
- Se precisar assumir algo, liste a suposição separadamente, no final.
- Não repita cenários equivalentes.

## FORMATO
Tabela com as colunas: ID, Cenário, Tipo (positivo, negativo ou limite), Passos, Resultado esperado e Prioridade (alta, média ou baixa).
