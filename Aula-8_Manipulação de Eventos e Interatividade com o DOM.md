## <h1>Manipulação de Eventos e Interatividade com o DOM em JavaScript</h1>

Nesta oitava aula, vamos explorar a manipulação de eventos e a interatividade com o DOM (Document Object Model) em JavaScript. 
Eventos são ações que ocorrem em um documento HTML, como cliques de mouse, pressionamentos de tecla ou carregamento da página, e podemos manipulá-los para criar interações dinâmicas e responsivas.

<h3> Você é ótimo nos estudos, se chegou até aqui, pode ir até o final. </h3>


## **Adicionando Event Listeners**: 


Para responder a eventos em elementos HTML, usamos os Event Listeners. Eles aguardam por um determinado evento e executam uma função específica quando o evento ocorre. Por exemplo:
```
let botao = document.getElementById("meuBotao");
botao.addEventListener("click", function() {
    console.log("O botão foi clicado!");
});

```


##  



## **Manipulando Eventos**: 


Dentro da função do Event Listener, você pode acessar informações sobre o evento que ocorreu usando o objeto event. Por exemplo:
```
let botao = document.getElementById("meuBotao");
botao.addEventListener("click", function(event) {
    console.log("Coordenadas do clique: ", event.clientX, event.clientY);
});

```
##  


## **Acesso ao DOM**: 


JavaScript permite acessar e manipular elementos HTML usando métodos como getElementById(), getElementsByClassName(), getElementsByTagName() ou querySelector(). Por exemplo:
```
let paragrafos = document.getElementsByTagName("p");
for (let i = 0; i < paragrafos.length; i++) {
    paragrafos[i].style.color = "blue";
}
```
##  


## **Manipulação do DOM**: 


Além de acessar, podemos modificar o conteúdo, estrutura e estilo dos elementos HTML no DOM. Por exemplo:
```
let titulo = document.getElementById("titulo");
titulo.textContent = "Novo Título"; // Modifica o texto do elemento
titulo.style.color = "red"; // Modifica a cor do texto

```
##  


## **Eventos de Carregamento**: 


Podemos executar código JavaScript assim que o documento HTML é carregado usando o evento DOMContentLoaded. Por exemplo:
```
document.addEventListener("DOMContentLoaded", function() {
    console.log("Documento HTML carregado!");
});
```
##  


Estes são os conceitos básicos de manipulação de eventos e interatividade com o DOM em JavaScript. Na próxima aula, vamos explorar bibliotecas e frameworks JavaScript populares, como jQuery e React, que simplificam o desenvolvimento web.
