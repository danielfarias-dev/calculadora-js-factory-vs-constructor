# Calculadora em JavaScript — Factory Function vs Constructor Function

Este projeto é uma calculadora simples, implementada **duas vezes**, usando duas abordagens diferentes de criação de objetos em JavaScript puro (Vanilla JS). O objetivo foi comparar os dois estilos na prática, como exercício de fixação de conceitos de POO em JavaScript.

## 🏭 `factory-function/`

Implementação usando uma **Factory Function** — uma função comum que recebe dados e devolve um objeto pronto (`return {...}`), aproveitando **closures** para manter o estado da calculadora.

## 🏗️ `constructor-function/`

Implementação usando uma **Constructor Function** — usa a palavra-chave `this` e `new` para criar instâncias, o mesmo padrão usado por trás das `class` do JavaScript.

## O que pratiquei neste projeto

- Manipulação do DOM (`querySelector`, `addEventListener`, `classList`)
- Diferença entre `this` (Constructor Function) e closures (Factory Function)
- Dois estilos diferentes de estruturar o mesmo comportamento em JavaScript
- Eventos de teclado modernos (`key`, `keydown`) no lugar de `keyCode` (deprecated)
- Tratamento de erros com `try/catch`

## Como rodar

Basta abrir o `index.html` de qualquer uma das pastas (`factory-function` ou `constructor-function`) diretamente no navegador.

## Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla JS, sem frameworks)

---

Projeto feito como parte dos meus estudos para me tornar desenvolvedor full stack.
