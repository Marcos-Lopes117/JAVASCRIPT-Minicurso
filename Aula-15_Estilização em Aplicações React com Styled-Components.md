## <h1> Estilização em Aplicações React com Styled-Components </h1>

Nesta décima quinta aula, vamos explorar uma abordagem moderna para estilização de componentes em aplicações React usando a biblioteca styled-components. O styled-components permite escrever estilos CSS diretamente dentro de seus componentes, facilitando o desenvolvimento e manutenção de estilos em sua aplicação.
##


## **Instalação do styled-components**: 


Antes de começar a usar o styled-components, é necessário instalá-lo em seu projeto React. Você pode instalar o styled-components usando npm ou yarn. Por exemplo:
```
npm install styled-components
```
ou
```
yarn add styled-components
```
##


## **Uso Básico do styled-components**: 


Após a instalação, você pode começar a usar o styled-components para estilizar seus componentes React. Você pode criar um componente estilizado usando a função styled e passando o elemento HTML desejado. Por exemplo:
```javascript
import styled from 'styled-components';

const Botao = styled.button`
    background-color: #007bff;
    color: #ffffff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
`;

function MeuComponente() {
    return <Botao>Clique Aqui</Botao>;
}
```
##


## **Passagem de Props para Estilização Condicional**: 


O styled-components permite passar props para seus componentes estilizados e usar essas props para estilização condicional. Isso é útil para criar componentes reutilizáveis com diferentes estilos. Por exemplo:
```javascript
const Botao = styled.button`
    background-color: ${props => props.primary ? '#007bff' : '#ffffff'};
    color: ${props => props.primary ? '#ffffff' : '#007bff'};
    padding: 10px 20px;
    border: ${props => props.primary ? 'none' : '1px solid #007bff'};
    border-radius: 5px;
    cursor: pointer;
`;

function MeuComponente() {
    return (
        <div>
            <Botao primary>Clique Aqui</Botao>
            <Botao>Clique Aqui Também</Botao>
        </div>
    );
}

```

##


## **Estilização de Componentes Dinâmicos**: 


Você também pode estilizar componentes dinâmicos, como componentes com estados diferentes ou componentes que respondem a eventos específicos. O styled-components oferece suporte para isso de forma intuitiva e simples.
##


O styled-components é uma ferramenta poderosa para estilizar componentes em aplicações React de forma eficiente e modular. Na próxima aula, vamos explorar outra abordagem para estilização em React usando CSS Modules. 
