## <h1>Requisições HTTP em React com Fetch e Axios</h1>


Nesta décima terceira aula, vamos explorar como fazer requisições HTTP em aplicações React para interagir com APIs externas. Isso é útil para buscar e enviar dados de e para um servidor, permitindo que sua aplicação web seja dinâmica e interativa.
##



**Usando Fetch API**: O Fetch API é uma interface JavaScript moderna para fazer requisições HTTP. Ela fornece uma maneira simples e poderosa de buscar recursos da web e enviar dados para servidores. Por exemplo:

```
  fetch('https://api.example.com/data')
    .then(response => response.json())
    .then(data => console.log(data))
    .catch(error => console.error('Erro:', error));

```

##  



**Tratando Requisições Assíncronas**: Como as requisições HTTP são assíncronas, é necessário lidar com as respostas usando Promises ou async/await para garantir que o código seja executado corretamente. Por exemplo:

```
async function fetchData() {
    try {
        const response = await fetch('https://api.example.com/data');
        const data = await response.json();
        console.log(data);
    } catch (error) {
        console.error('Erro:', error);
    }
}

fetchData();

```

##  


**Usando Axios**: O Axios é uma biblioteca JavaScript amplamente utilizada para fazer requisições HTTP em navegadores e no Node.js. Ele fornece uma API mais amigável e intuitiva em comparação com o Fetch API. Por exemplo:##  
```
import axios from 'axios';

axios.get('https://api.example.com/data')
    .then(response => console.log(response.data))
    .catch(error => console.error('Erro:', error));

```

##


**Enviando Dados com POST**: Além de buscar dados, você também pode enviar dados para um servidor usando o método POST. Com o Fetch API ou Axios, você pode enviar dados em formato JSON ou formulário. Por exemplo:

```
const data = { nome: 'João', idade: 30 };

axios.post('https://api.example.com/dados', data)
    .then(response => console.log(response.data))
    .catch(error => console.error('Erro:', error));

```
##


Fazer requisições HTTP em aplicações React é uma parte importante do desenvolvimento de aplicações web modernas e dinâmicas. Na próxima aula, vamos explorar como lidar com rotas em aplicações React usando React Router, uma biblioteca popular para roteamento declarativo.
