---
title: variáveis e constantes
date: 2023-04-27 13:35:49
tags:
category: javascript
---

# Variáveis e Constantes no JavaScript

JavaScript é uma linguagem de programação dinâmica e flexível que permite aos desenvolvedores declarar variáveis e constantes para armazenar valores em seu código.
Variáveis

Uma variável é um espaço de armazenamento que pode conter um valor ou uma referência a um valor. No JavaScript, as variáveis são declaradas usando a palavra-chave var, let ou const. Por exemplo, para declarar uma variável chamada idade com um valor de 30, podemos usar o seguinte código:

```javascript
var idade = 30;

let idade = 30;

const idade = 30;
```

As variáveis declaradas com a palavra-chave var ou let podem ter seus valores alterados ao longo do tempo, enquanto as variáveis declaradas com a palavra-chave const são constantes e não podem ter seus valores alterados.

```javascript
let nome = "João";
nome = "Maria"; // valor alterado

const PI = 3.1415;
PI = 3; // erro, o valor de uma constante não pode ser alterado
```

### Constantes

As constantes são variáveis que têm um valor imutável. Em outras palavras, o valor atribuído a uma constante não pode ser alterado depois que a constante é declarada. No JavaScript, as constantes são declaradas usando a palavra-chave const. Por exemplo:

```javascript
const PI = 3.1415;
```

Ao declarar uma constante, é necessário atribuir um valor a ela. Se nenhum valor for atribuído, ocorrerá um erro.

```javascript
const PI; // erro, uma constante precisa ter um valor atribuído
```

### Escopo de Variáveis e Constantes

O escopo de uma variável ou constante é a parte do código onde ela pode ser acessada. No JavaScript, existem dois tipos de escopos: escopo global e escopo local.

Variáveis e constantes declaradas fora de uma função têm escopo global, o que significa que elas podem ser acessadas em todo o código.

```javascript
var nome = "João"; // variável global

function exemplo() {
  console.log(nome); // "João" será impresso no console
}

exemplo();
```

Variáveis e constantes declaradas dentro de uma função têm escopo local, o que significa que elas só podem ser acessadas dentro dessa função.

```javascript
function exemplo() {
  var nome = "João"; // variável local
  console.log(nome); // "João" será impresso no console
}

exemplo();
console.log(nome); // erro, a variável nome não pode ser acessada fora da função exemplo
```

### Conclusão

As variáveis e constantes são ferramentas essenciais para o desenvolvimento em JavaScript. Elas permitem que os desenvolvedores armazenem valores e referências a valores em seus códigos, além de ajudar a manter a organização e a legibilidade do código. É importante entender a diferença entre variáveis e constantes, bem como o escopo em que elas são definidas, para evitar erros e maximizar a eficiência do código.

