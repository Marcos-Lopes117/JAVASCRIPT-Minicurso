## <h1>Formulários e validação em React</h1>


Nesta décima segunda aula, vamos aprender como lidar com formulários em React e como realizar validação de entrada de dados. Formulários são uma parte essencial de muitas aplicações web, e React oferece maneiras convenientes de trabalhar com eles.

<h3> Não há obstáculos que não possam ser tranformados em aprendizado. </h3>

## **Controlando Componentes de Formulário**: 


Em React, os componentes de formulário, como input, textarea e select, são controlados, o que significa que o estado deles é controlado pelo React. Para isso, você deve usar o estado do componente para armazenar e atualizar os valores dos campos do formulário. Por exemplo:
```
import React, { useState } from 'react';

function Formulario() {
    const [nome, setNome] = useState('');

    function handleChange(event) {
        setNome(event.target.value);
    }

    function handleSubmit(event) {
        event.preventDefault();
        alert('Nome submetido: ' + nome);
    }

    return (
        <form onSubmit={handleSubmit}>
            <input type="text" value={nome} onChange={handleChange} />
            <button type="submit">Enviar</button>
        </form>
    );
}
```
##  


## **Validação de Entrada de Dados**: 


Em muitos casos, é necessário validar os dados inseridos pelos usuários antes de enviá-los para o servidor. Você pode realizar validação de entrada de dados em React usando condicionais para verificar se os dados são válidos ou não. Por exemplo:
```
import React, { useState } from 'react';

function Formulario() {
    const [email, setEmail] = useState('');
    const [erro, setErro] = useState('');

    function handleChange(event) {
        setEmail(event.target.value);
    }

    function handleSubmit(event) {
        event.preventDefault();
        if (email.includes('@')) {
            alert('Email submetido: ' + email);
            setErro('');
        } else {
            setErro('Email inválido');
        }
    }

    return (
        <form onSubmit={handleSubmit}>
            <input type="email" value={email} onChange={handleChange} />
            <button type="submit">Enviar</button>
            {erro && <p>{erro}</p>}
        </form>
    );
}

```
##  


## **Usando Bibliotecas de Validação**: 


Em aplicações mais complexas, pode ser útil usar bibliotecas de validação de formulários, como Formik ou Yup. Essas bibliotecas fornecem ferramentas poderosas para lidar com validação de entrada de dados em formulários React.
##  


## **Feedback Visual**: 

É importante fornecer feedback visual aos usuários durante o processo de validação de formulários. Você pode exibir mensagens de erro, destacar campos inválidos e fornecer instruções claras para os usuários corrigirem os problemas.
##


Compreender como lidar com formulários e realizar validação de entrada de dados é crucial para o desenvolvimento de aplicações web interativas e robustas em React. Na próxima aula, vamos explorar como fazer requisições HTTP em React para interagir com APIs externas.
