# Description

Back end for the Alfa Romeo Store Project

## Installation

```bash
$ npm install
```

## Running the app

```bash
# init Prisma and Docker (please verify docker is installed)

# init docker and Prisma
$ npm install @prisma/cli
$ prisma:dev:generate
$ npm run db:dev:restart

# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```