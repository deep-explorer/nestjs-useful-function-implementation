# NestJS-Useful-Functions

* NestJS 9
* TypeORM 0.3

## Installation

```bash
npm ci
```

## Running the app

```bash
npm run start:dev
```

## Repl

```bash
NODE_ENV=development npm run start:repl
```

*https://docs.nestjs.com/recipes/repl*

## Databse

### Create db

```bash
psql -U postgres

create database development_nestjs_example;
```

### Create migration

```bash
NODE_ENV=development npm run db:migration:create
```

### Run migration

```bash
NODE_ENV=development npm run db:migration:run
```

### Sync schema

```bash
NODE_ENV=development npm run db:schema:sync
```
