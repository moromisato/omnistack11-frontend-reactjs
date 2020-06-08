# omnistack11-frontend-reactjs


<p align="center">
<img src="https://github.com/moromisato/omnistack11-frontend-reactjs/blob/master/src/assets/logo.svg" width="150" heigh="93" />
<br>
Projeto criado durante a semana oministack 11
</p>
A semana omnistack é um curso gratuito de uma semana que envolve a criação de uma aplicação completa desde o backend até o <i>frontend</i> e <i>mobile</i>.
Cada semana omnistack possui um projeto diferente, na 11ª versão da semana o projeto proposto é um gerenciador de incidentes para ongs, onde as ongs podem se cadastrar e adicionar seus incidentes que precisam de algum tipo de levantamento de verbas,
assim, os usuários do sistema podem visualizar esses incidentes e ajudar as ongs doando algum valor.

Este repositório contém o <i>frontend</i> da aplicação, feito em ReactJS e utiliza as seguintes bibliotecas: 

* [react-router-dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom) para realizar a navegação

* <a href="https://github.com/axios/axios"><i>Axios</i></a> para realizar requisições http

# Rodando o projeto

Para que esse projeto funcione corretamente é necessário clonar o [backend da aplicação](https://github.com/moromisato/omnistack11-backend) e seguir os passos para rodar ele primeiro, depois que o *backend* estiver rodando basta:

Clonar ou baixar o projeto, após isso instalar as dependências:
<br><i>npm install</i>

Em seguida é necessário iniciar o servidor do ReactJs:
<br><i>npm start</i>

E pronto, agora é só acessar http://localhost:3000.

# Funcionalidades

## Login
<p align="center">
<img src="https://github.com/moromisato/omnistack11-frontend-reactjs/blob/master/src/assets/screenshots/Screenshot%20from%202020-06-08%2014-18-56.png" width="800" heigh="530" />
<p>

Clicanco no botão "Não tenho cadastro", você será redirecionado para página de cadastro de ONGS, após realizar o cadastro você receberá o *id* necessário para fazer o *login*.

## Cadastro de ongs
<p align="center">
<img src="https://github.com/moromisato/omnistack11-frontend-reactjs/blob/master/src/assets/screenshots/Screenshot%20from%202020-06-08%2014-19-00.png" width="800" heigh="530" />
<p>

## Cadastro de incidentes
<p align="center">
<img src="https://github.com/moromisato/omnistack11-frontend-reactjs/blob/master/src/assets/screenshots/Screenshot%20from%202020-06-08%2014-18-49.png" width="800" heigh="530" />
<p>

## Listagem de incidentes
Aqui também é possível deletar os incidentes por meio do botão em formato de lixeira no canto superior direito de cada incidente.
<p align="center">
<img src="https://github.com/moromisato/omnistack11-frontend-reactjs/blob/master/src/assets/screenshots/Screenshot%20from%202020-06-08%2014-18-39.png" width="800" heigh="530" />
<p>



