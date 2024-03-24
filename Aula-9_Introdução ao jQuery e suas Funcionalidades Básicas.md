## <h1>Introdução ao jQuery e suas Funcionalidades Básicas</h1>

Nesta nona aula, vamos introduzir o jQuery, uma biblioteca JavaScript popular que simplifica a manipulação do DOM, o tratamento de eventos, a animação e várias outras tarefas comuns no desenvolvimento web. Vamos explorar algumas de suas funcionalidades básicas.

<h3> Bem vindo a área de Frameworks, agora é só consolidar os estudos. </h3>


## **Importando o jQuery**: 


Antes de usar o jQuery, você precisa importá-lo no seu documento HTML. Você pode fazer isso incluindo o jQuery de um CDN ou baixando-o localmente e referenciando-o em seu arquivo HTML. Por exemplo:
```
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

```
##  


## **Seleção de Elementos**: 


Assim como no JavaScript puro, você pode selecionar elementos do DOM usando seletores CSS no jQuery. Por exemplo:
```
// Selecionando elementos por ID
let elemento = $("#meuElemento");

// Selecionando elementos por classe
let elementos = $(".minhaClasse");

// Selecionando elementos por tipo
let paragrafos = $("p");

```

##  


## **Manipulação de Elementos**: 


O jQuery oferece uma variedade de métodos para manipular elementos do DOM, como adicionar, remover ou modificar atributos, estilos, conteúdo e estrutura. Por exemplo:
```
// Modificando o conteúdo de um elemento
$("#meuParagrafo").text("Novo conteúdo");

// Adicionando uma classe a um elemento
$(".meuElemento").addClass("minhaClasse");

// Ocultando um elemento
$("#minhaDiv").hide();

```
##  


## **Eventos**: 


O jQuery simplifica a manipulação de eventos, permitindo adicionar e remover manipuladores de eventos de forma fácil e direta. Por exemplo:
```
// Adicionando um manipulador de evento de clique
$("#meuBotao").click(function() {
    alert("Botão clicado!");
});

// Removendo um manipulador de evento de clique
$("#meuBotao").off("click");

```
##  


## **Animação**: 


O jQuery facilita a criação de animações em elementos do DOM, oferecendo uma variedade de métodos para animar propriedades como tamanho, posição, opacidade, entre outras. Por exemplo:
```
// Animando a opacidade de um elemento
$("#minhaDiv").fadeIn();

```

##  


Esses são apenas alguns dos recursos básicos do jQuery. Na próxima aula, vamos explorar um framework JavaScript moderno e poderoso chamado React, que é amplamente utilizado para criar interfaces de usuário interativas e responsivas. 
