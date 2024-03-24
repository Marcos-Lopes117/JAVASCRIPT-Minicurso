## <h1>Manipulação de Arrays e Objetos</h1>

Nesta quarta aula, vamos aprofundar nossos conhecimentos sobre manipulação de arrays e objetos em JavaScript. Vamos explorar como adicionar, remover e iterar sobre elementos em arrays, assim como adicionar, remover e atualizar propriedades em objetos.

 <h3> Seu conhecimento já está se tornando avançado, prossiga!. </h3>

##  **Adição de Elementos em Arrays**: 


Você pode adicionar elementos a um array usando métodos como push(), unshift() ou atribuindo diretamente a um índice específico. Por exemplo:
```javascript
let numeros = [1, 2, 3];
numeros.push(4); // Adiciona 4 ao final do array
numeros.unshift(0); // Adiciona 0 ao início do array
numeros[5] = 5; // Adiciona 5 ao final do array

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Remoção de Elementos em Arrays**:  


Você pode remover elementos de um array usando métodos como pop(), shift() ou splice(). Por exemplo:
```javascript
let numeros = [1, 2, 3, 4, 5];
numeros.pop(); // Remove o último elemento (5)
numeros.shift(); // Remove o primeiro elemento (1)
numeros.splice(1, 1); // Remove o elemento no índice 1 (2)

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Iteração sobre Arrays**:  


Você pode iterar sobre os elementos de um array usando loops como for ou métodos como forEach(). Por exemplo:
```javascript
let numeros = [1, 2, 3, 4, 5];
for (let i = 0; i < numeros.length; i++) {
    console.log(numeros[i]);
}

numeros.forEach(function(numero) {
    console.log(numero);
});


```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Adição e Atualização de Propriedades em Objetos**: 


Você pode adicionar novas propriedades a um objeto simplesmente atribuindo um valor a uma nova chave, e atualizar propriedades existentes atribuindo um novo valor a uma chave existente. Por exemplo:
```javascript
let pessoa = {
    nome: "Marcos",
    idade: 34
};

pessoa.casado = true; // Adiciona a propriedade 'casado'
pessoa.idade = 35; // Atualiza a propriedade 'idade'

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


## **Remoção de Propriedades em Objetos**:  


Você pode remover propriedades de um objeto usando o operador delete. Por exemplo:
```javascript
let pessoa = {
    nome: "Marcos",
    idade: 35
};

delete pessoa.idade; // Remove a propriedade 'idade'

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


Estes são alguns dos conceitos essenciais de manipulação de arrays e objetos em JavaScript. Na próxima aula, vamos explorar funções de array mais avançadas, como map, filter e reduce, que são muito úteis em situações de programação do dia a dia. 
