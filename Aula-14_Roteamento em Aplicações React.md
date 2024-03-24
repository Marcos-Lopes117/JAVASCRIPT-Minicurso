## <h1>Roteamento em Aplicações React com React Router</h1>


Nesta décima quarta aula, vamos aprender sobre roteamento em aplicações React utilizando a biblioteca React Router. O roteamento é fundamental para criar aplicações de página única (SPA) com várias visualizações e URLs amigáveis.
## 


## **Instalação do React Router**: 


Antes de começar a usar o React Router, é necessário instalá-lo em seu projeto React. Você pode instalar o React Router DOM usando npm ou yarn. Por exemplo:
```
npm install react-router-dom
```
ou
```
yarn add react-router-dom
```
##  


## **Configuração das Rotas**: 


Após a instalação, você pode começar a configurar as rotas em sua aplicação React. O React Router fornece componentes como BrowserRouter, Route e Switch para definir e renderizar as rotas. Por exemplo:
```
import { BrowserRouter as Router, Route, Switch } from 'react-router-dom';
import Home from './components/Home';
import Sobre from './components/Sobre';
import Contato from './components/Contato';

function App() {
    return (
        <Router>
            <Switch>
                <Route exact path="/" component={Home} />
                <Route path="/sobre" component={Sobre} />
                <Route path="/contato" component={Contato} />
            </Switch>
        </Router>
    );
}


```
##  


## **Navegação entre Rotas**: 


Para criar links de navegação entre as rotas, você pode usar o componente Link fornecido pelo React Router. Isso permite que os usuários naveguem entre diferentes visualizações de forma suave e sem recarregar a página. Por exemplo:
```
import { Link } from 'react-router-dom';

function Menu() {
    return (
        <nav>
            <ul>
                <li><Link to="/">Home</Link></li>
                <li><Link to="/sobre">Sobre</Link></li>
                <li><Link to="/contato">Contato</Link></li>
            </ul>
        </nav>
    );
}

```
##  


## **Parâmetros de Rota**: 


Você pode passar parâmetros para suas rotas para torná-las dinâmicas. Por exemplo, você pode ter uma rota para exibir detalhes de um item específico em sua aplicação. Por exemplo:##
```
<Route path="/produto/:id" component={DetalhesProduto} />

```
##


## **Redirecionamento e Rotas Aninhadas**: 


O React Router oferece suporte para redirecionamento de URLs e rotas aninhadas, permitindo criar layouts complexos e fluxos de navegação avançados em sua aplicação React.

Usar o React Router é uma maneira eficaz de gerenciar o roteamento em aplicações React, permitindo criar experiências de usuário sofisticadas e responsivas. Na próxima aula, vamos explorar como adicionar estilos a aplicações React usando bibliotecas como styled-components ou CSS modules.
