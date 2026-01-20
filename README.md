# ProEventos

> Projeto desenvolvido no início dos meus estudos em desenvolvimento Full-Stack, como parte do curso "Seja Full-Stack com .NET Web API e Angular + EF Core". O objetivo foi aprender os fundamentos de backend com .NET e frontend com Angular, além de práticas como autenticação, autorização, upload de imagens, paginação, filtros e integração entre as tecnologias.

## Sobre o Projeto

O ProEventos é uma aplicação para gerenciamento de eventos, permitindo cadastro, edição, exclusão e visualização de eventos, lotes, palestrantes e redes sociais. O sistema é dividido em duas partes principais:

- **Backend:** API REST desenvolvida em .NET 5, utilizando Entity Framework Core, autenticação JWT, Identity, e arquitetura em múltiplas camadas.
- **Frontend:** Aplicação Angular, com formulários reativos, rotas, autenticação, upload de imagens e layout responsivo.

## Funcionalidades

- Cadastro e gerenciamento de eventos
- Gerenciamento de lotes de ingressos
- Cadastro de palestrantes e suas redes sociais
- Upload de imagens para eventos e palestrantes
- Autenticação e autorização de usuários (JWT)
- Paginação e filtros de pesquisa

## Como Executar o Projeto

### Pré-requisitos

- [.NET 5 SDK](https://dotnet.microsoft.com/download/dotnet/5.0)
- [Node.js](https://nodejs.org/)

### Backend (.NET API)

1. Acesse a pasta do backend:
   ```bash
   cd Back/src/ProEventos.API
   ```
2. Restaure os pacotes e execute as migrações (caso necessário):
   ```bash
   dotnet restore
   dotnet ef database update
   ```
3. Inicie a API:
   ```bash
   dotnet run
   ```
   A API estará disponível em `https://localhost:5001` ou `http://localhost:5000`.

### Frontend (Angular)

1. Acesse a pasta do frontend:
   ```bash
   cd Front/ProEventos-App
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie a aplicação Angular:
   ```bash
   npm start
   ```
   O frontend estará disponível em `http://localhost:4200`.

## Observações

- Este projeto foi feito no início dos meus estudos, então pode conter práticas e padrões básicos.
- Sinta-se à vontade para usar como referência ou base para estudos.

## Contato

Em caso de dúvidas ou sugestões, entre em contato pelo [Twitter @programadament](https://twitter.com/programadament) ou [Facebook](http://facebook.com/ozirispc).

## Licença

Este projeto é livre e de código aberto, distribuído sob a licença MIT.

### ProEventos - Curso da Udemy

# Seja Full-Stack com .NET Web API e Angular + EF Core - V2.0 - [Course](http://www.udemy.com/course/angular-dotnetcore-efcore/?referralCode=F44264DF39DEEE45EC50).

This is all of the files for our Course about Angular, WebAPI and More

The Summary is:

1.  Introdução ao Curso
2.  NET Core 5
3.  EF Core 5 - Introdução
4.  Angular - Introdução
5.  Angular - Interpolação, Diretivas e Binding
6.  .NET 5 - Múltiplas Camadas
7.  Angular - Organizar, Rota, Alertas e Mais
8.  Angular - Reactive Forms e Novo Layout
9.  DTOs & Data Annotations
10. Angular - Registrando Evento
11. Angular e .NET - Eventos e Lotes
12. Upload de Imagens
13. Asp .NET Core Identity - Autenticar e Autorizar - (TOKEN - JWT)
14. Angular + .NET Core Identity + JWT
15. Paginação e Filtros
16. Palestrantes e Redes Sociais - Backend
17. Palestrantes e Redes Sociais - Frontend
18. Palestrantes e Eventos (2022)
19. Docker + MySQL (2022)

If you want to see this link course, really in action [original site](https://www.programadamente.com).

## Basic Setup

1. [Install Node.js](https://nodejs.org/)
1. [Install .NET Core 5](https://dotnet.microsoft.com/download/)
1. Fork the [ProEventos](https://github.com/vsandrade/ProEventos/fork)
1. Clone the repo you just forked.

## User Settings

```
# Site settings
title: Vinícius de Andrade - Professor and Full-stack Developer
description: A Course about [Angular, .NET Core and EF Core]
baseurl: "" # the subpath of your site, e.g. /blog/ or empty.

# User settings
There're not settings exactly, only files to guide you understand a little bit more about Angular, WebAPI and More
```

## Questions

Having a problem getting something to work or want to know why I setup something in a certain way? Ping me on Twitter [@programadament](https://twitter.com/programadament) or Message on [Facebook](http://facebook.com/ozirispc)

## Donation

If you liked my work, [subscribe on youtube](https://www.youtube.com/user/ozirispc?sub_confirmation=1)
Or buy the course using [this link](http://www.udemy.com/course/angular-dotnetcore-efcore/?referralCode=F44264DF39DEEE45EC50).

## License

This theme is free and open source software, distributed under the The MIT License. So feel free to use this files on your site without linking back to me or using a disclaimer.

If you’d like to give me credit somewhere on your blog or tweet a shout out to [@ozirispc](https://twitter.com/ozirispc), that would be pretty sweet.
