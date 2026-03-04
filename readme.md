# 🧪 Primeira Automação de Testes UI com Cypress

Este é meu primeiro projeto de automação de testes end-to-end utilizando
**Cypress**, aplicado sobre a funcionalidade de login do sistema:

🔗 https://automationpratice.com.br/login

------------------------------------------------------------------------

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com fins de estudo e marca o início da
minha jornada prática em automação de testes.

Objetivos principais:

-   Entender a estrutura do Cypress
-   Criar meus primeiros cenários automatizados
-   Validar fluxo de login (positivo e negativo)
-   Praticar organização e escrita de testes
-   Ganhar confiança com automação UI

------------------------------------------------------------------------

## 🛠 Tecnologias Utilizadas

-   Cypress
-   JavaScript
-   Node.js

------------------------------------------------------------------------

## 📂 Estrutura do Projeto

``` bash
cypress/
 ├── e2e/
 │    └── login.cy.js
 ├── fixtures/
 ├── support/
cypress.config.js
package.json
```

------------------------------------------------------------------------

## ✅ Cenários Automatizados

-   ✔ Login com usuário válido
-   ✔ Login com senha inválida
-   ✔ Tentativa de login com campos vazios
-   ✔ Validação de mensagens de erro

------------------------------------------------------------------------

## 🧠 Principais Aprendizados

Durante o desenvolvimento deste projeto aprendi:

-   Como funciona a estrutura de testes no Cypress
-   Diferença entre `describe` e `it`
-   Uso do `cy.visit()`
-   Como localizar elementos na tela
-   Como validar mensagens com `should`
-   Como organizar testes de forma legível
-   A importância de nomes claros nos cenários

Também enfrentei dificuldades como:

-   Configuração inicial do ambiente
-   Entendimento de erros no console
-   Ajustes para o Cypress reconhecer corretamente os testes

Esses desafios foram fundamentais para meu aprendizado.

------------------------------------------------------------------------

## 🚀 Como Executar o Projeto

``` bash
npm install
npx cypress open