# Prisma / Turborepo Template

This is a template monorepo using turborepo.

## What's inside?

This turborepo includes the following packages/apps:

### Apps and Packages

- `web`: a [Next.js](https://nextjs.org) app
- `config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `database`: [Prisma](https://prisma.io/) ORM wrapper to manage & access your database
- `tsconfig`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting
- [Prisma](https://prisma.io/) for database ORM
- [Tailwind](https://tailwindcss.com) for styling

### Database

We use [Prisma](https://prisma.io/) to manage & access our database. As such you will need a database for this project, either locally or hosted in the cloud. I recommend [PlanetScale](https://planetscale.com/)

You will need to update the `DATABASE_URL` in your `.env` accordingly.

If you are using PlanetScale you can push your db changes with the following command

```bash
yarn run db:push
```

### Build

To build all apps and packages, run the following command:

```bash
yarn run build
```

### Develop

To develop all apps and packages, run the following command:

```bash
yarn run dev
```
