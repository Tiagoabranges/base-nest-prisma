<h1 align="center"> Projeto base NestJS com Prisma </h1>
Este é um projeto base para construir aplicativos web com Node.js, NestJS, Prisma, PostgreSQL e TypeScript.

Como usar
Pré-requisitos
Node.js (v14.x ou superior)
npm ou yarn
PostgreSQL (v12.x ou superior)

## ✔️ Técnicas e tecnologias utilizadas

- ``Node.js``
- ``NestJS``
- ``Prisma``
- ``PostgreSQL``
- ``TypeScript``
- ``docker``



## Se for usar uma imagem docker do postgres, utilize esse comando

``docker run --name my-postgres -e POSTGRES_PASSWORD=mysecretpassword -p 5432:5432 -d postgres``


# 🛠️ Estrutura do projeto
<h4> O projeto possui a seguinte estrutura:</h4>


.
├── dist/                   `` Arquivos compilados para JavaScript``

├── node_modules/           `` Dependências do projeto``

├── prisma/                 `` Arquivos de configuração do Prisma``

│   ├── migrations/         `` Arquivos de migração do banco de dados``

│   ├── schema.prisma       `` Arquivo de definição do schema do Prisma``

├── src/                    `` Código fonte do projeto``

│   ├── app.controller.ts  `` Controlador principal do NestJS``

│   ├── app.module.ts      `` Módulo principal do NestJS``

│   ├── app.service.ts     `` Serviço principal do NestJS``

│   ├── main.ts            `` Arquivo de entrada do servidor``

│   ├── models/            `` Modelos de dados do projeto``

│   └── prisma/            `` Prisma Client para acesso ao banco de dados``

├── .env.example            `` Exemplo de arquivo de variáveis de ambiente``

├── .gitignore              `` Arquivo de configuração do Git``

├── package.json            `` Arquivo de configuração do projeto ``
