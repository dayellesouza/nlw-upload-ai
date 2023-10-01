# UPLOAD AI

Esse projeto consiste em uma aplicação que recebe um video e utiliza o ChatGPT para gerar titulos e/ou uma descrição para o YouTube.

## Tecnologias 🛠
Esse projeto foi desenvolvido utilizando as seguintes tecnologias:

* React
* TypeScript
* TailwindCSS
* Vite.js
* Radix UI
* Shadcn/ui
* ffmpeg
* Node.js
* Prisma
* Fastify
* Zod
* SQLite
* OpenAI Node API

## Instalação e execução

### Pré requisitos

É necessário ter o programa do [Git](https://git-scm.com/) intalado. Para clonar utilize o comando a seguir:

```bash
https://github.com/dayellesouza/nlw-upload-ai.git
```

Para instalar as dependências e executar o projeto é necessário ter instalado em sua máquina o [node.js](https://nodejs.org/en), que vem acompanhado do npm.

Este projeto usa [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/#windows-stable) como gerenciador de pacotes:

```bash
npm install --global yarn
```

### API

Acesse a pasta back-end do projeto e rode o seguinte comando:

```bash
cd upload-ai-api
yarn install
```

Para gerar o client do Prisma:

```bash
yarn prisma generate
```

Para executar as migrações:

```bash
yarn prisma migrate dev
```

Crie um arquivo '.env' com as variáveis a seguir: 

```bash
DATABASE_URL="file:./dev.db"
OPENAI_KEY="Chave de API gerada"
```
**IMPORTANTE**: Necessário ter uma conta na OpenAI. Obtenha sua chave da API e preencha o campo OPENAI_KEY com a mesma.

Executar o projeto em modo de desenvolvimento:

```bash
yarn run dev
```

### WEB
Acesse a pasta front-end do projeto e rode o seguinte comando:

```bash
cd upload-ai-web
yarn install
```

Executar o projeto em modo de desenvolvimento:

```bash
yarn run dev
```

A aplicação pode ser encontrada no caminho http://localhost:5173

## Autora

<a href="https://github.com/dayellesouza">
 <img style="border-radius: 50%;" src="https://github.com/dayellesouza.png" width="100px;" alt="Dayelle's Profile"/>
 <br />
</a>

Feito com 💜 por Dayelle Souza
