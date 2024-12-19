<h1 align="center">First API</h1>

Uma API REST com sistema de rotas e CRUD de usuários. Sem conexão com  bando de dados, utilizado um mock estático com dados fakes. Desenvolvido como projeto de estudo.

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=CONCLUÍDO&color=GREEN&style=for-the-badge)

## :hammer_and_wrench: Tecnologias
As seguintes ferramentas foram usadas na construção do projeto:
- [Node.js (v22.12.0)](<https://nodejs.org/en/>)
- [npm (v10.9.2)](https://www.npmjs.com/)
- [VSCode (v1.95.3)](https://code.visualstudio.com/)
- [Insomnia(v10.2.0)](https://insomnia.rest/)

## :computer: Funcionalidades e Demonstração da Aplicação

No Controller se encontram as regras de negócio(métodos para CRUD de usuários):

- `listUsers()`: Lista os usuários em ordem ascendente ou descendente

- `getUserById()`: Retorna um usuário com ID correspondente

- `createUser()`:  Cria um novo usuário

- `updateUser()`: Atualiza dados de um usuário existente

- `deleteUser()`: Deleta usuário com ID correspondente

O `bodyParser()` é um Event Listener que executa automaticamente quando a requisição for POST ou PUT.

## :open_file_folder: Acesso ao Projeto
```
#Baixar arquivos manualmente ou clonar repositório
$ git clone [url_projeto]
```

## :gear: Executar
```
#Abrir projeto e executar aplicação no terminal do VSCode
$ node src/index.js
```

No Insomnia, testar as rotas com os métodos GET, POST, PUT e DELETE | URL -> http://localhost:3000/users/:id

## Pessoas Desenvolvedoras do Projeto

Stephanie de França

## Licenses
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
