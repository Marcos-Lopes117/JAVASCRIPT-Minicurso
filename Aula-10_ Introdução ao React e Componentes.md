## <h1> Introdução ao React e Componentes em JavaScript</h1>

Nesta décima aula, vamos introduzir o React, um framework JavaScript de código aberto mantido pelo Facebook e uma comunidade de desenvolvedores. O React é amplamente utilizado para criar interfaces de usuário interativas e responsivas em aplicações web.

## Frameworks como react são usados constantemente por grandes empresas.


**O que é o React?:**
O React é uma biblioteca JavaScript usada para construir interfaces de usuário (UI) baseadas em componentes reutilizáveis. Ele permite criar aplicativos web complexos dividindo-os em pequenos componentes, tornando-os mais fáceis de entender, desenvolver e manter.
##


**Componentes em React:** 
Um componente em React é uma parte isolada e reutilizável de uma interface de usuário. Os componentes podem ser definidos como funções ou classes em JavaScript e podem ter seu próprio estado interno e props (propriedades).
##


**Criando um Componente Funcional**: Um componente funcional é uma função JavaScript que retorna elementos JSX (JavaScript XML), descrevendo a aparência do componente. Por exemplo:
```
let botao = document.getElementById("meuBotao");
botao.addEventListener("click", function() {
    console.log("O botão foi clicado!");
});

```

##  



**Criando um Componente de Classe**: Um componente de classe é uma classe JavaScript que estende a classe React.Component e implementa um método render() para retornar elementos JSX. Por exemplo:
```
import React, { Component } from 'react';

class MeuComponente extends Component {
    render() {
        return <h1>Olá, mundo!</h1>;
    }
}

```

##  


**Renderização de Componentes**: Para renderizar um componente React, você pode usar o método ReactDOM.render(), fornecendo o componente e o elemento DOM onde deseja renderizá-lo. Por exemplo:
```
import React from 'react';
import ReactDOM from 'react-dom';
import MeuComponente from './MeuComponente';

ReactDOM.render(<MeuComponente />, document.getElementById('root'));
```

##  


Esses são os conceitos básicos de componentes em React. Na próxima aula, vamos explorar como passar dados para componentes usando props e como gerenciar o estado interno de um componente.
