# Desafio de Automação usando o Cypress.io

Para executar os testes, é necessário ter o [Node.js](https://nodejs.org/en/) instalado.

## Instalação
Instalação do [Cypress](https://docs.cypress.io/guides/getting-started/installing-cypress) via npm:
```bash
npm install cypress --save-dev
````
Para rodar os testes, execute o comando:
```bash
cypress open
```

## Desafio I
Página: http://www.buscacep.correios.com.br
- A. Realizar a busca com o valor “69005-040”
- B. Realizar a busca com o valor “Lojas Bemol”

## Desafio II
Automatizar o fluxo definido abaixo:
1. Acessar o site http://www.trivago.com.br
2. Digitar o valor “Manaus” no campo de busca
3. Clicar no botão "Pesquisar" Selecionar a opção Ordenar por “Avaliação e
Sugestões"
4. Verifique o nome do primeiro da lista
5. Verifique a avaliação do primeiro da lista
6. Verifique o valor do primeiro da lista
