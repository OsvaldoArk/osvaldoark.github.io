---
title: Operadores Javascript
date: 2023-04-28 15:40:03
author: Osvaldo Souza
tags:
category: javascript
---

Os operadores em JavaScript são símbolos que indicam ao interpretador do JavaScript para executar operações em um ou mais valores. Os operadores são amplamente utilizados em programação para realizar cálculos matemáticos, comparações e outras tarefas.

Existem vários tipos de operadores em JavaScript, incluindo operadores aritméticos, operadores de atribuição, operadores de comparação, operadores lógicos, operadores bit a bit e operadores ternários. Neste artigo, vamos examinar cada um desses tipos de operadores e ver como eles são usados em JavaScript.

### Operadores Aritméticos
Os operadores aritméticos em JavaScript são usados para realizar operações matemáticas básicas, como adição, subtração, multiplicação e divisão. Aqui estão os operadores aritméticos mais comuns em JavaScript:

\+ (Adição): Este operador é usado para adicionar dois valores.
\- (Subtração): Este operador é usado para subtrair um valor de outro valor.
\* (Multiplicação): Este operador é usado para multiplicar dois valores.
/ (Divisão): Este operador é usado para dividir um valor por outro valor.
% (Módulo): Este operador é usado para encontrar o resto da divisão entre dois valores.
++ (Incremento): Este operador é usado para aumentar um valor em 1.
-- (Decremento): Este operador é usado para diminuir um valor em 1.

Exemplo de uso:

```javascript

let x = 5;
let y = 10;

let soma = x + y; // soma será igual a 15
let subtracao = y - x; // subtracao será igual a 5
let multiplicacao = x * y; // multiplicacao será igual a 50
let divisao = y / x; // divisao será igual a 2
let resto = y % x; // resto será igual a 0
let incremento = ++x; // x será igual a 6
let decremento = --y; // y será igual a 9
```

### Operadores de Atribuição
Os operadores de atribuição em JavaScript são usados para atribuir um valor a uma variável. Aqui estão os operadores de atribuição mais comuns em JavaScript:

= (Atribuição): Este operador é usado para atribuir um valor a uma variável.
+= (Atribuição de Adição): Este operador é usado para adicionar um valor a uma variável e atribuir o resultado à mesma variável.
-= (Atribuição de Subtração): Este operador é usado para subtrair um valor de uma variável e atribuir o resultado à mesma variável.
*= (Atribuição de Multiplicação): Este operador é usado para multiplicar uma variável por um valor e atribuir o resultado à mesma variável.
/= (Atribuição de Divisão): Este operador é usado para dividir uma variável por um valor e atribuir o resultado à mesma variável.

Exemplo de uso:

```javascript

let x = 5;
x += 10; // x será igual a 15
x -= 3; // x será igual a 12
x *= 2; // x será igual a 24
x /= 4; // x será igual a 6
```

### Operadores de Comparação
Os operadores de comparação em JavaScript são usados para comparar dois valores e retornar um valor booleano (true ou false) indicando se a comparação é verdadeira ou falsa. Aqui estão os operadores de comparação mais comuns em JavaScript:

== (Igual): Este operador compara se dois valores são iguais.
!= (Diferente): Este operador compara se dois valores são diferentes.
=== (Estritamente Igual): Este operador compara se dois valores são iguais e do mesmo tipo de dados.
!== (Estritamente Diferente): Este operador compara se dois valores são diferentes ou de tipos diferentes.

(Maior que): Este operador compara se um valor é maior que outro valor.

< (Menor que): Este operador compara se um valor é menor que outro valor.

= (Maior ou Igual): Este operador compara se um valor é maior ou igual a outro valor.

<= (Menor ou Igual): Este operador compara se um valor é menor ou igual a outro valor.

Exemplo de uso:

```javascript

let x = 5;
let y = 10;

console.log(x == 5); // retorna true
console.log(x != y); // retorna true
console.log(x === '5'); // retorna false
console.log(x !== '5'); // retorna true
console.log(y > x); // retorna true
console.log(x < y); // retorna true
console.log(y >= 10); // retorna true
console.log(x <= 4); // retorna false
```

### Operadores Lógicos
Os operadores lógicos em JavaScript são usados para combinar duas ou mais expressões lógicas e retornar um valor booleano (true ou false). Aqui estão os operadores lógicos mais comuns em JavaScript:

&& (E): Este operador retorna true se todas as expressões lógicas forem verdadeiras.
|| (Ou): Este operador retorna true se pelo menos uma das expressões lógicas for verdadeira.
! (Não): Este operador inverte o valor da expressão lógica.

Exemplo de uso:

```javascript

let x = 5;
let y = 10;

console.log(x > 3 && y < 15); // retorna true
console.log(x > 10 || y < 5); // retorna false
console.log(!(x == y)); // retorna true
```
### Operadores Bit a Bit
Os operadores bit a bit em JavaScript são usados para manipular valores binários (zeros e uns) em nível de bit. Eles são usados principalmente para operações de baixo nível, como criptografia, compactação de dados e manipulação de imagens. Aqui estão os operadores bit a bit mais comuns em JavaScript:

& (E): Este operador realiza uma operação de E bit a bit em dois valores.
| (Ou): Este operador realiza uma operação de OU bit a bit em dois valores.
~ (Não): Este operador inverte todos os bits de um valor.
^ (XOR): Este operador realiza uma operação de OU exclusivo bit a bit em dois valores.
<< (Deslocamento à Esquerda): Este operador move os bits de um valor para a esquerda.

(Deslocamento à Direita): Este operador move os bits de um valor para a direita.

Exemplo de uso:

```javascript

let x = 5;
let y = 10;

console.log(x & y); // retorna 0
console.log(x | y); // retorna 15
console.log(~x); // retorna -6
console.log(x ^ y); // retorna 15
console.log(x << 1); // retorna 10
console.log(y >> 1); // retorna 5
```

### Operadores de Atribuição
Os operadores de atribuição em JavaScript são usados para atribuir um valor a uma variável. Aqui estão os operadores de atribuição mais comuns em JavaScript:

= (Atribuição): Este operador atribui um valor a uma variável.
+= (Atribuição de Adição): Este operador adiciona um valor a uma variável.
-= (Atribuição de Subtração): Este operador subtrai um valor de uma variável.
*= (Atribuição de Multiplicação): Este operador multiplica um valor por uma variável.
/= (Atribuição de Divisão): Este operador divide um valor por uma variável.
%= (Atribuição de Módulo): Este operador atribui o resto de uma divisão a uma variável.
<<= (Atribuição de Deslocamento à Esquerda): Este operador move os bits de um valor para a esquerda e atribui o resultado a uma variável.
\>>= (Atribuição de Deslocamento à Direita): Este operador move os bits de um valor para a direita e atribui o resultado a uma variável.
&= (Atribuição de E Bit a Bit): Este operador realiza uma operação de E bit a bit e atribui o resultado a uma variável.
|= (Atribuição de OU Bit a Bit): Este operador realiza uma operação de OU bit a bit e atribui o resultado a uma variável.
^= (Atribuição de OU Exclusivo Bit a Bit): Este operador realiza uma operação de OU exclusivo bit a bit e atribui o resultado a uma variável.

Exemplo de uso:

```javascript
let x = 5;
let y = 10;

x += y; // x agora é igual a 15
y *= 2; // y agora é igual a 20
x %= 6; // x agora é igual a 3
y <<= 2; // y agora é igual a 80
```


### Conclusão
Os operadores em JavaScript são fundamentais para realizar operações matemáticas, comparações, combinações lógicas e manipulação de bits. É importante entender como esses operadores funcionam e como eles podem ser usados em diferentes situações. Com a prática e o estudo contínuo, é possível se tornar um programador mais eficiente e habilidoso em JavaScript.
