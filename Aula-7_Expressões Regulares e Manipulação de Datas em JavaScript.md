## <h1>Expressões Regulares e Manipulação de Datas em JavaScript</h1>

Nesta sétima aula, vamos explorar dois tópicos importantes em JavaScript: expressões regulares e manipulação de datas. 
Expressões regulares são padrões utilizados para encontrar determinados padrões em strings, enquanto a manipulação de datas permite trabalhar com datas e horários de forma eficiente.

<h3> A partir da próxima aula, você começa a aprender conceitos avançados de JS. 🚀 </h3>


## **Expressões Regulares**: 


As expressões regulares, também conhecidas como regex, são padrões de texto usados para buscar e substituir partes de uma string. Em JavaScript, você pode criar expressões regulares usando a classe RegExp ou utilizando diretamente a sintaxe literal entre barras (/). Por exemplo:
```javascript
let regex = /hello/;
let texto = "Olá, hello mundo!";
console.log(regex.test(texto)); // Saída: true
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  



## **Métodos de Expressões Regulares**: 


JavaScript oferece diversos métodos para trabalhar com expressões regulares, como test(), exec(), match(), search() e replace(). Por exemplo:
```javascript
let texto = "Olá, mundo!";
let regex = /mundo/;
console.log(regex.test(texto)); // Saída: true
console.log(texto.match(regex)); // Saída: ["mundo"]
console.log(texto.search(regex)); // Saída: 5
console.log(texto.replace(regex, "amigo")); // Saída: "Olá, amigo!"
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Manipulação de Datas**: 


JavaScript possui um objeto embutido chamado Date para trabalhar com datas e horas. Você pode criar um novo objeto Date com a data e hora atuais ou com um valor específico. Por exemplo:
```javascript
let dataAtual = new Date();
console.log(dataAtual); // Saída: Data e hora atual

let nascimento = new Date(1990, 5, 15);
console.log(nascimento); // Saída: Data de nascimento

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Métodos de Manipulação de Datas**: 

O objeto Date possui diversos métodos para manipular datas, como getFullYear(), getMonth(), getDate(), getDay(), getHours(), getMinutes(), getSeconds(), entre outros. Por exemplo:
```javascript
let hoje = new Date();
console.log(hoje.getFullYear()); // Ano atual
console.log(hoje.getMonth()); // Mês atual (0-11)
console.log(hoje.getDate()); // Dia do mês atual
console.log(hoje.getDay()); // Dia da semana (0-6, 0 é Domingo)
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


Estes são os conceitos básicos de expressões regulares e manipulação de datas em JavaScript. Na próxima aula, vamos abordar conceitos avançados e práticos, como manipulação de eventos e interações com o DOM (Document Object Model).
