## <h1>Manipulação de Strings e Métodos de String</h1>

Nesta sexta aula, vamos explorar como manipular strings e os principais métodos de string disponíveis em JavaScript. 
As strings são sequências de caracteres, e JavaScript oferece uma variedade de métodos para manipular e trabalhar com elas.

<h3> Você já está quase no fim do módulo básico, Parabéns DEV. 👌 </h3>


## **Concatenação de Strings**: 


Você pode concatenar strings usando o operador de adição (+) ou o método concat(). Por exemplo:
```javascript
let nome = "João";
let sobrenome = "Silva";
let nomeCompleto = nome + " " + sobrenome;
console.log(nomeCompleto); // Saída: "João Silva"

let mensagem = "Olá, ".concat(nome, "!");
console.log(mensagem); // Saída: "Olá, João!"
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  



## **Tamanho de uma String**: 


Você pode obter o tamanho de uma string usando a propriedade length. Por exemplo:
```javascript
let texto = "Esta é uma string.";
console.log(texto.length); // Saída: 18
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Acesso a Caracteres**: 


Você pode acessar caracteres individuais em uma string usando a notação de colchetes ([]). Lembre-se de que os índices de string em JavaScript começam em zero. Por exemplo:
```javascript
let texto = "JavaScript";
console.log(texto[0]); // Saída: "J"
console.log(texto[4]); // Saída: "S"
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).
##  


## **Métodos Encadeados**: 


Você pode encadear várias chamadas de métodos de array para realizar operações complexas em uma única linha de código. Por exemplo: propriedades existentes atribuindo um novo valor a uma chave existente. Por exemplo:
```javascript
let numeros = [1, 2, 3, 4, 5];
let resultado = numeros.filter(function(numero) {
    return numero % 2 === 0;
}).map(function(numero) {
    return numero * 2;
});
console.log(resultado); // Saída: [4, 8]

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Métodos de String**: 


JavaScript oferece uma variedade de métodos de string para manipulação, como toUpperCase(), toLowerCase(), slice(), indexOf(), substring(), replace(), entre outros. Por exemplo:
```javascript
let frase = "JavaScript é incrível!";
console.log(frase.toUpperCase()); // Saída: "JAVASCRIPT É INCRÍVEL!"
console.log(frase.indexOf("incrível")); // Saída: 13
console.log(frase.slice(0, 10)); // Saída: "JavaScript"
console.log(frase.replace("incrível", "fantástica")); // Saída: "JavaScript é fantástica!"
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Divisão e Junção de Strings**: 


Você pode dividir uma string em substrings usando o método split() e unir substrings em uma única string usando o método join(). Por exemplo:
```javascript
let lista = "maçã, banana, uva";
let frutas = lista.split(", ");
console.log(frutas); // Saída: ["maçã", "banana", "uva"]

let frase = frutas.join(" e ");
console.log(frase); // Saída: "maçã e banana e uva"
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


Estes são alguns dos principais métodos e operações para manipulação de strings em JavaScript. 
Na próxima aula, vamos abordar conceitos avançados, como expressões regulares e manipulação de datas. 
