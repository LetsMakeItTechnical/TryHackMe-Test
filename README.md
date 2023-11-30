# TryHackMe-Test

### Prerequisites

**Node version 16.x**

### Cloning the repository

```shell
git clone https://github.com/LetsMakeItTechnical/TryHackMe-Test.git
```

### Features

- **Next.js 13**: Frontend and server-side rendering for a seamless user experience.
- **Prisma ORM**: Robust database interactions with support for complex queries and migrations.

### Run Postgres Container Locally

```shell
npm run docker
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
DATABASE_URL=postgres://POSTGRES_USER:POSTGRES_PASSWORD@localhost:5432/task
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |

