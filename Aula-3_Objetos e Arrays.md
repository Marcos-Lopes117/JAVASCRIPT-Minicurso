## <h1>Objetos e arrays</h1>

Nesta terceira aula, vamos explorar objetos e arrays em JavaScript. Ambos são estruturas de dados fundamentais que permitem armazenar e manipular conjuntos de valores.
<h3> Você esta ficando bom em JS, mantenha o foco e conquiste a habilidade. </h3>


## **Arrays**: 

Um array é uma coleção ordenada de valores, acessíveis por um índice numérico. Em JavaScript, os arrays podem conter qualquer tipo de dado, incluindo números, strings, booleanos, objetos e até mesmo outros arrays. Por exemplo:
```javascript
let numeros = [1, 2, 3, 4, 5];
let nomes = ["Ana", "João", "Maria"];
let misto = [1, "dois", true, { chave: "valor" }];
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  



## **Acesso a Elementos de um Array**: 

Você pode acessar elementos de um array utilizando seu índice dentro de colchetes. Lembre-se de que os índices de array em JavaScript começam em zero. Por exemplo:
```javascript
let numeros = [10, 20, 30, 40, 50];
console.log(numeros[0]); // Saída: 10
console.log(numeros[2]); // Saída: 30

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Objetos**: 


Um objeto é uma coleção de pares chave-valor, onde as chaves são strings e os valores podem ser de qualquer tipo de dado, incluindo números, strings, booleanos, arrays e até mesmo outras funções e objetos. Por exemplo:
```javascript
let pessoa = {
    nome: "Ana",
    idade: 25,
    casada: false,
    interesses: ["música", "esportes", "viajar"]
};
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Acesso a Propriedades de um Objeto**: 


Você pode acessar as propriedades de um objeto utilizando a notação de ponto (objeto.propriedade) ou a notação de colchetes (objeto['propriedade']). Por exemplo:
```javascript
let pessoa = {
    nome: "Ana",
    idade: 25
};

console.log(pessoa.nome); // Saída: "Ana"
console.log(pessoa['idade']); // Saída: 25
```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


##  **Métodos de Objeto**:  


Além de propriedades, os objetos em JavaScript também podem conter métodos, que são funções associadas ao objeto. Por exemplo:
```javascript
let pessoa = {
    nome: "Marcos Lopes",
    idade: 25,
    saudacao: function() {
        console.log("Olá, meu nome é " + this.nome + "!");
    }
};

pessoa.saudacao(); // Saída: "Olá, meu nome é Marcos Lopes!"

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


Estes são os conceitos básicos de objetos e arrays em JavaScript. Na próxima aula, vamos explorar mais sobre manipulação de arrays e objetos, incluindo adição, remoção e iteração sobre seus elementos.  Continue para próxima aula.

