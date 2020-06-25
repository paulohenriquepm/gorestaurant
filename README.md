<h1 align="center">
    <img alt="GoRestaurant" src="https://ik.imagekit.io/hwyksvj4iv/gorestaurant_soSmYKHra.svg" width="250px" />
    <p align="center">
      <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/paulohenriquepm/gorestaurant">
      <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/paulohenriquepm/gorestaurant">
      <img alt="Stars" src="https://img.shields.io/github/stars/paulohenriquepm/gorestaurant">
      <img alt="Repository Size" src="https://img.shields.io/github/repo-size/paulohenriquepm/gorestaurant">
    </p>
</h1>

<h1 align="center">
   <img alt="GoRestaurant Web" src="https://res.cloudinary.com/paulohenriquepm/image/upload/v1593090962/gorestaurant-web_s8zlip.gif" />
</h1>

# GoRestaurant
  GoRestaurant é uma aplicação destinada a gestão de pratos de um restaurante de comida italiana. O dono do restaurante consegue adicionar, editar e excluir pratos que serão
visualizados por seus clientes.

  Os dados são consumidos via uma API Fake utlizando-se do json-server.

## Requisitos
- Ter [**Git**](https://git-scm.com/) instalado para clonar o projeto.
- Ter [**Node.js**](https://nodejs.org/en/) instalado.

## Instalação

```bash
  #Clonando a aplicação
  $ git clone https://github.com/paulohenriquepm/gorestaurant

  #Entrando no diretório recem clonado
  $ cd gorestaurant
  
  #Instalando dependências
  $ yarn
```

## Rodando aplicação

Primeiramente, você deve iniciar o servidor json para consumir os dados.

```bash
  #Rodando servidor
  $ json-server server.json -p 3333
```

Agora, em um outro terminal, inicie a página Web.

```bash
  #Rodando página Web
  $ yarn start
```

Por fim, acesse [localhost](http://localhost:3000) para visualizar a aplicação.


Feito com ❤ por Paulo Henrique 👋 [Get in touch!](https://github.com/paulohenriquepm)
