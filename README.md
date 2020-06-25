
<div align="center">

# :rocket: GoStack - Desafio 3 - Conceitos do React Native


[![NODE](https://img.shields.io/badge/node-10.16.0-green.svg)](https://nodejs.org/en/)  [![NPM](https://img.shields.io/badge/npm-6.14.5-green.svg)](https://nodejs.org/en/) [![YARN](https://img.shields.io/badge/yarn-1.19.0-blue.svg)](https://yarnpkg.com/) [![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)



Terceiro desafio em React Native do Bootcamp GoStack da RocketSeat.

Neste desafio foi proposto desenvolver o frontend mobile da aplicação para se comunicar com o backend desenvolvido no [Desafio1](https://github.com/pablohdev/desafio-conceito-node-express), utilizando o axios para requisições com o nosso backend, tendo a opção de listar e curtir os repositórios cadastrado pelo front web da aplicação.
</div>



___
##  :pick: O que usamos

   |                    | Dependencias |
   | ------------------ | ------------ |
   | :heavy_check_mark: | React        |
   | :heavy_check_mark: | React-Native |
   | :heavy_check_mark: | ReactDom     |
   | :heavy_check_mark: | Axios        |
___


## Instalação

Clone o repositorio e execute o comando abaixo para instalar as dependencias.


```sh
   yarn
```

ou 


```sh
    npm install
```

Para executar a aplicação:

```sh
    yarn android
      #ou
    yarn ios
```

ou 


```sh
    npm android
       #ou
    npm ios
```


##  :bus: Rotas utilizadas na aplicação



   | Método | Rota                   |                             |
   | ------ | ---------------------- | --------------------------- |
   | GET    | /repositories/         | Lista todos os repositórios |
   | POST   | /repositories/:id/like | Dá like em um repositório   |
   



## :satisfied: Obrigado 

Created ♥ by [Pablo Henrique](https://linkedin.com/in/pablohdev)
