# mini-estoque

Projetinho feito em aula para praticar **NestJS** com **Prisma ORM**, simulando um sistema simples de controle de estoque.

## Tecnologias

- [NestJS](https://nestjs.com/)
- [Prisma ORM](https://www.prisma.io/)
- [MySQL](https://www.mysql.com/)
- TypeScript

##  Pré-requisitos

- Node.js >= 18
- npm
- MySQL rodando localmente (ou em container)

## Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/mini-estoque.git
cd mini-estoque
```

Instale as dependências:

```bash
npm install
```

##  Configuração

Crie um arquivo `.env` na raiz do projeto com a string de conexão do MySQL:

```env
DATABASE_URL="mysql://usuario:senha@localhost:3306/mini_estoque"
```

## Banco de Dados (Prisma)

Gerar o client do Prisma:

```bash
npx prisma generate
```

Rodar as migrations:

```bash
npx prisma migrate dev
```

Visualizar o banco com o Prisma Studio:

```bash
npx prisma studio
```

## Executando o projeto

```bash
# desenvolvimento
npm run start:dev

# produção
npm run build
npm run start:prod
```

A aplicação estará disponível em `http://localhost:3000`.

## Obs:
Projeto criado com fins de estudo/aula, focado em praticar integração entre NestJS e Prisma ORM com banco MySQL.
