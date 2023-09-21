a# Ecommerce Admin

![Ecommerce-admin](https://i.postimg.cc/rczsW-CB4/ecommerce-admin.png)

### [Live Site](https://ecommerce-admin-iota-sepia.vercel.app/)

## Introduction
Full Stack E-Commerce + Dashboard & CMS: Next.js 13 App Router, React, Tailwind, Prisma, MySQL, Clerk Auth.

The e-commerce admin dashboard is a user interface specifically designed to manage and control the operations of an online store or e-commerce platform.

### Tech Stack 💻 :
- NextJS
- React
- TailwindCSS
- Mysql
- Prisma
- Clerk Auth
- ShadcnUI

### Cloning the repository

```shell
git clone https://github.com/inifarhan/ecommerce-admin.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

# This was inserted by `prisma init`:
# Environment variables declared in this file are automatically made available to Prisma.
# See the documentation for more detail: https://pris.ly/d/prisma-schema#accessing-environment-variables-from-the-schema

# Prisma supports the native connection string format for PostgreSQL, MySQL, SQLite, SQL Server, MongoDB and CockroachDB.
# See the documentation for all the connection string options: https://pris.ly/d/connection-strings

DATABASE_URL=
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
STRIPE_API_KEY=
FRONTEND_STORE_URL=
STRIPE_WEBHOOK_SECRET=
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
