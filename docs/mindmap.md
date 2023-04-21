---
markmap:
  color:
    - "#2b2b2b"
    - "#fbca16"
    - "#ca16fb"
    - "#16fbca"
  colorFreezeLevel: 3
  initialExpandLevel: 1
---

# Cypress

## Para que serve

- End-to-End
- UI / Interface de Usuário
- APIs
- Componentes

## Tecnologias

- Node
- Javascript / TS
- Mocha
- Chai
  - chai-jquery
  - sinon-chai
- Assíncrono

## Limitações

- Permanentes
  - Não é uma ferramenta "genérica" de automação
  - Comandos são executados diretamente no navegador
  - Não é possível controlar dois navegadores ao mesmo tempo
  - Não há suporte para testes em múltiplas abas
  - Diferentes domínios no mesmo teste (resolvido com o cy.origin)
  
- Temporárias
  - Hover
  - Tecla TAB
  - Eventos nativos do navegador
  - Suporte nativo a iframes

## Boas práticas

- Organização dos testes
- Controle do estado da aplicação
- Uso de seletores adequados
- Uso de aliases para armazenar valores
- Testes independentes
- Enriquecer testes com asserções
- Usar ganchos (hooks) antes do teste
- Evitar esperas desnecessárias
- Usar recursos globais como a URL base

## Comandos

- Buscar elementos
  - get
  - contains
  - contextuais
    - find
    - closest
    - prev, prevAll
    - next, nextAll, nextUntil
    - fist, last, eq
    - parent, parents, parentsUntil
- Interagir com elementos
  - type
  - click
  - select
  - check, uncheck
- Manipulação de arquivos
  - writeFile
  - readFile
  - fixture
- Mocks e Simulações
  - intercept
  - spy
  - stub
  - tick
  - clock
- Manipulação do navegador
  - clearCookie, clearCookies
  - onBeforeLoad
  - onLoad
- Asserções
  - assert
  - should
  - expect

## Principais plugins

- cypress-grep
- cypress-allure-plugin
- cypress-plugin-api
- cypress-iframe
- cypress-cucumber-preprocessor

## Pessoas para acompanhar

- Agilizei
- Cypress Ambassadors

## Onde aprender

- Cypress Direto ao Ponto