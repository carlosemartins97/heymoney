<h1 align="center">dt money</h1>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  {{app_name}} 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Começando</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-dados">Dados</a> &#xa0; | &#xa0;
  <a href="https://github.com/carlosemartins97" target="_blank">Autor</a>
</p>

<br>

## :dart: Sobre ##

O dt money é uma dashboard com intuito de gerenciar as economias do usuário de forma rápida e prática, dando oportunidade ao usuário cadastrar novas transações e exibi-las em tela.
A aplicação não ultiliza um back end e banco de dados real. Porém, foi utilizado o MirageJS para realizar a integração com uma "fake api" para coletar dados de forma dinâmica, 
facilitando ao trocar o url da api posteriormente. <br>
<br>

A aplicação ainda não está em estado final, por conta disso, pode conter alguns erros.

<p align="center"> 
 <img  src="https://i.imgur.com/QtonhGQ.gif" alt="dt money dashboard">
</p>

## :sparkles: Features ##

:heavy_check_mark: Registrar novas transações;\
:heavy_check_mark: Exibir histórico transações;\
:heavy_check_mark: Realizar cálculo de entradas e saídas de economias;

## :rocket: Tecnologias ##

As seguintes tecnologias foram utilizadas no projeto:

- [React](https://pt-br.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Styled-Components](https://styled-components.com/)
- [MirageJS](https://miragejs.com/)

## :white_check_mark: Requerimentos ##

Antes de começar :checkered_flag:, você precisa ter [Git](https://git-scm.com) e [Node](https://nodejs.org/en/) instalados.

## :checkered_flag: Começando ##

```bash
# Clone this project
$ git clone https://github.com/carlosemartins97/heymoney

# Access
$ cd heymoney

# Install dependencies
$ yarn install

# Run the project
$ yarn start

# The server will initialize in the <http://localhost:3000>
```

## :checkered_flag: Dados ##
```
#Go to root dir
$ cd heymoney

#Open index.tsx


```
Transactions is an array that contains all the data. The structure must follow:
```
transactions: [
        {
          id: 1,
          title: 'Freelancer de website',
          type: 'deposit',
          category: 'Dev',
          amount: 6000,
          createdAt: new Date('2021-02-12 09:00:00')
        },
#Feel free to add how many data you want.
```



Feito com :heart: por <a href="https://github.com/carlosemartins97" target="_blank">Carlos Eduardo Martins</a>

&#xa0;

<a href="#top">Back to top</a>
