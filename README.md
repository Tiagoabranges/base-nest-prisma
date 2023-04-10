<h1 align="center"> Projeto base NestJS com Prisma </h1>
Este é um projeto base para construir aplicativos web com Node.js, NestJS, Prisma, PostgreSQL e TypeScript.

Como usar
Pré-requisitos
Node.js (v14.x ou superior)
npm ou yarn
PostgreSQL (v12.x ou superior)
Instalação
Clone o repositório em sua máquina:

# 📁 Acesso ao projeto


git clone https://github.com/seu-usuario/nestjs-prisma-base.git
Entre na pasta do projeto:

cd nestjs-prisma-base
Instale as dependências:


npm install
Configure o banco de dados PostgreSQL:

Crie um banco de dados vazio para o seu projeto.
Abra o arquivo .env na raiz do projeto e atualize as informações do banco de dados de acordo com suas configurações.
Execute as migrações do banco de dados:


npm run prisma:migrate
Inicie o servidor:


npm run start
Acesse http://localhost:3000 no seu navegador para testar a aplicação.

Scripts disponíveis
npm run start: Inicia o servidor em modo de desenvolvimento.
npm run build: Compila o código TypeScript em JavaScript para a pasta dist/.
npm run prisma:migrate: Executa as migrações do Prisma para atualizar o banco de dados.
npm run prisma:generate: Gera os arquivos do Prisma Client baseados no seu schema do Prisma.
npm run format: Formata o código usando o Prettier.
npm run lint: Executa a verificação de linting usando o ESLint.
## ✔️ Técnicas e tecnologias utilizadas

- ``Node.js``
- ``NestJS``
- ``Prisma``
- ``PostgreSQL``
- ``TypeScript``





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