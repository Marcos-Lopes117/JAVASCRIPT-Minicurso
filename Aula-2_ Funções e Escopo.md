## <h1>Funções e Escopo</h1>

Nesta segunda aula, vamos explorar funções e escopo em JavaScript. 
Uma função em JavaScript é um bloco de código que realiza uma tarefa específica quando é chamado ou invocado. Ela pode aceitar entradas, chamadas de parâmetros, realizar operações com essas entradas e retornar um resultado. Funções são utilizadas para modularizar o código, tornando-o mais organizado, reutilizável e fácil de dar manutenção. Em resumo, uma função em JavaScript é uma maneira de agrupar um conjunto de instruções relacionadas para serem executadas quando necessário.

## Continue focado nos estudos! Prepare um cafézinho e aproveite.

<img src="/img/func1.png">

**Declaração de Funções**: Você pode declarar funções em JavaScript usando a palavra-chave function. Por exemplo:
```
<script>
function saudacao() {
    console.log("Olá, Bem vindo a Aula 2!");
}

saudacao(); // Chamando a função
</script>

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


<img src="/img/func2.png">

**Parâmetros e Argumentos**: Você pode passar informações para uma função usando parâmetros. Por exemplo:
```
function saudar(nome) {
    console.log("Olá, " + nome + "!");
}

saudar("Ana"); // Passando "Ana" como argumento

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  

**Retorno de Função**: As funções podem retornar valores usando a palavra-chave return. Por exemplo:
```
function somar(a, b) {
    return a + b;
}

let resultado = somar(3, 5);
console.log(resultado);
// Saída: 8

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  

**Escopo de Variáveis**: Em JavaScript, as variáveis podem ter escopo global ou escopo local. Variáveis declaradas dentro de uma função têm escopo local, enquanto variáveis declaradas fora de todas as funções têm escopo global. Por exemplo:
```
let global = "Variável global";

function teste() {
    let local = "Variável local";
    console.log(local);
    console.log(global);
}

teste();
// Saída: "Variável local" e "Variável global"
console.log(local);
// Erro: local is not defined

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


**Funções Anônimas e Arrow Functions**:  Além da declaração tradicional de funções, você pode criar funções anônimas e usar arrow functions. Por exemplo:
```
// Função anônima
let saudacao = function() {
    console.log("Olá, mundo!");
};

// Arrow function
let quadrado = (x) => {
    return x * x;
};

saudacao(); // Saída: "Olá, mundo!"
console.log(quadrado(3)); // Saída: 9

```
Copie o código e faça o teste no [compilador](https://onecompiler.com/javascript).

##  


Esses são os conceitos básicos de funções e escopo em JavaScript. Na próxima aula, vamos explorar objetos e arrays, que são fundamentais para a programação em JavaScript. Continue para próxima aula.


