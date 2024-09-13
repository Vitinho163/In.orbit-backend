<h1 align="center">In.orbit: Back-End</h1>

<div align="center">
  <a href="#english">English</a> |
  <a href="#portugues">Português</a>
</div>

---

# English <a name="english"></a>

In.orbit - Back-End is a **Node.js** application developed as part of Rocketseat's NLW Pocket event. It's a goal manager where users can create weekly goals, track progress, and view a summary of completed goals with a progress bar.

## Summary

- [Technologies Used](#technologies-used-en)
- [Project Structure](#project_structure_en)
- [Installation](#installation-en)
- [Deploy](#deploy-en)
- [Author](#author-en)

## 🚀 Technologies Used <a name="technologies-used-en"></a>

- **[Node.js](https://nodejs.org/)**: JavaScript runtime built on Chrome's V8 engine.
- **[Fastify](https://www.fastify.io/)**: Fast and low overhead web framework for Node.js.
- **[@paralleldrive/cuid2](https://github.com/paralleldrive/cuid2)**: Secure, collision-resistant IDs for applications.
- **[Day.js](https://day.js.org/)**: Fast and lightweight date library for JavaScript.
- **[PostgreSQL](https://www.postgresql.org/)**: Powerful, open-source object-relational database system.
- **[Zod](https://zod.dev/)**: TypeScript-first schema declaration and validation library.
- **[Drizzle ORM](https://github.com/drizzle-team/drizzle-orm)**: Lightweight TypeScript ORM.
- **[Biome](https://biomejs.dev/)**: Tool for formatting and linting code.

## 📁 Structure of the project <a name="project_structure_en"></a>

```
├── src: directory containing application source files

│ ├── db: directory containing database connection, schema, and seed files.

│ ├── functions: directory containing exported function files (create-goal-completion, create-goal, get-week-pending-goals, get-week-summary).

│ ├── http: directory containing routes and server initialization files.

│ | ├── routes: directory with all the application routes.

| | └── server.ts: file initializing the application.

│ ├── env.ts: file validating environment variables with Zod.

├── .env.example: example file for environment variables.
```

## 🛠️ Installation <a name="installation-en"></a>

1. Clone the repository or download the ZIP file from the repository.
```bash
git clone https://github.com/Vitinho163/In.orbit-backend.git
```

2. Install dependencies:
```bash
npm install
```

3. Rename the `.env.example` file to `.env` and fill in the information:
```bash
DATABASE_URL="postgresql://docker@localhost:5432/inorbit"
```

4. Run the migration:
```bash
npx drizzle-kit migrate
```

5. Start the server:
```bash
npm run dev
```

## 💻 Deploy <a name="deploy-en"></a>

The back-end of this project is hosted on Render and can be accessed at:
```
https://in-orbit-backend.onrender.com/
```

>Note: The application may take some time to respond if it's been idle due to Render's free tier limitations.

<div align="center" name="author-en">
  <h4>Created with ❤️ by <a href="https://github.com/Vitinho163">João Victor</a></h4>
</div>

---

# Português <a name="portugues"></a>

In.orbit - Back-End é uma aplicação **Node.js** desenvolvida durante a NLW Pocket da Rocketseat. É um gerenciador de metas onde os usuários podem cadastrar metas semanais, acompanhar o progresso e visualizar o histórico de metas realizadas com uma barra de progresso.

## Sumário

- [Tecnologias Utilizadas](#tecnologias-usadas-pt)
- [Estrutura do Projeto](#estrutura-do-projeto-pt)
- [Instalação](#instalacao-pt)
- [Deploy](#deploy-pt)
- [Autor](#autor-pt)

## 🚀 Tecnologias Utilizadas <a name="tecnologias-usadas-pt"></a>

- **[Node.js](https://nodejs.org/)**: Ambiente de execução JavaScript baseado no motor V8 do Chrome.
- **[Fastify](https://www.fastify.io/)**: Framework web rápido e leve para Node.js.
- **[@paralleldrive/cuid2](https://github.com/paralleldrive/cuid2)**: Geração de IDs seguros e resistentes a colisões.
- **[Day.js](https://day.js.org/)**: Biblioteca de datas rápida e leve para JavaScript.
- **[PostgreSQL](https://www.postgresql.org/)**: Sistema de banco de dados relacional de código aberto.
- **[Zod](https://zod.dev/)**: Biblioteca de validação de esquemas baseada em TypeScript.
- **[Drizzle ORM](https://github.com/drizzle-team/drizzle-orm)**: ORM leve para TypeScript.
- **[Biome](https://biomejs.dev/)**: Ferramenta para formatação e linting de código.

## 📁 Estrutura do Projeto <a name="estrutura-do-projeto-pt"></a>

```
├── src: diretório contendo os arquivos da aplicação

│ ├── db: diretório contendo a conexão com o banco de dados, schema e seed.

│ ├── functions: diretório com os arquivos das funções exportadas (create-goal-completion, create-goal, get-week-pending-goals, get-week-summary).

│ ├── http: diretório com as rotas e arquivos de inicialização da aplicação.

│ | ├── routes: diretório contendo as rotas da aplicação.

| | └── server.ts: arquivo de inicialização da aplicação.

│ ├── env.ts: arquivo validando as variáveis de ambiente com Zod.

├── .env.example: arquivo de exemplo para variáveis de ambiente.
```

## 🛠️ Instalação <a name="instalacao-pt"></a>

1. Clone o repositório ou faça o download do arquivo ZIP:
```bash
git clone https://github.com/Vitinho163/In.orbit-backend.git
```

2. Instale as dependências:
```bash
npm install
```

3. Renomeie o arquivo `.env.example` para `.env` e preencha as informações:
```bash
DATABASE_URL="postgresql://docker@localhost:5432/inorbit"
```

4. Execute a migração:
```bash
npx drizzle-kit migrate
```

5. Inicie o servidor:
```bash
npm run dev
```

## 💻 Deploy <a name="deploy-pt"></a>

O back-end deste projeto está hospedado na Render e pode ser acessado em:
```
https://in-orbit-backend.onrender.com/
```

>Nota: A aplicação pode demorar para responder se estiver inativa devido às limitações do plano gratuito da Render.

<div align="center" name="autor-pt">
  <h4>Criado com ❤️ por <a href="https://github.com/Vitinho163">João Victor</a></h4>
</div>