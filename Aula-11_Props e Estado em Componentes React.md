## <h1>Props e Estado em Componentes React</h1>


Nesta décima primeira aula, vamos aprofundar nossos conhecimentos sobre React, focando em duas importantes características: props e estado. Entender como usar props e estado é fundamental para criar componentes dinâmicos e interativos em React.


<h3> Parabéns DEV! </h3>

## **Props (Propriedades)**: 

As props são passadas para um componente React como atributos e permitem que você envie dados de um componente pai para um componente filho. As props são somente leitura e não podem ser modificadas pelo componente filho. Por exemplo:
```
// Componente pai
function Pai() {
    return <Filho nome="João" idade={30} />;
}

// Componente filho
function Filho(props) {
    return <p>Nome: {props.nome}, Idade: {props.idade}</p>;
}

```

##  


## **Estado (State)**: 


O estado é uma característica de um componente React que representa dados mutáveis ​​que afetam a renderização do componente. O estado é gerenciado pelo próprio componente e pode ser alterado usando o método setState(). Por exemplo:
```
import React, { Component } from 'react';

class Contador extends Component {
    constructor(props) {
        super(props);
        this.state = { contador: 0 };
    }

    incrementarContador() {
        this.setState({ contador: this.state.contador + 1 });
    }

    render() {
        return (
            <div>
                <p>Contagem: {this.state.contador}</p>
                <button onClick={() => this.incrementarContador()}>Incrementar</button>
            </div>
        );
    }
}

```

##  


## **Atualizando o Estado**: 


Ao chamar o método setState(), o React atualiza o estado do componente e re-renderiza o componente para refletir as mudanças. O novo estado pode ser uma nova versão do estado anterior ou derivado do estado anterior. Por exemplo:
```
this.setState((prevState) => {
    return { contador: prevState.contador + 1 };
});

```


##  


## **Passando Funções como Props**: 


Você pode passar funções como props de um componente pai para um componente filho para permitir que o componente filho atualize o estado do componente pai. Isso é útil para comunicação entre componentes. Por exemplo:
```
// Componente pai
function Pai() {
    const [contador, setContador] = useState(0);

    return <Filho incrementar={() => setContador(contador + 1)} />;
}

// Componente filho
function Filho(props) {
    return <button onClick={props.incrementar}>Incrementar</button>;
}

```
##  



Esses são os conceitos fundamentais de props e estado em componentes React. Na próxima aula, vamos explorar como lidar com formulários em React e como realizar validação de entrada de dados.
