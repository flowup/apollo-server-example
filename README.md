# Apollo Server example

The purpose if this repo is to demonstrate how to implement a GraphQL API with the following tech stack:

- [Apollo Server](https://www.apollographql.com/docs/apollo-server/)
- [Express](https://expressjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [GraphQL code generator](https://graphql-code-generator.com/)

The API includes a schema and resolver implementation for a simple book catalogue (with a mock in-memory database).

## Prerequisites

Install [Node.js](https://nodejs.org/).

## First steps

Install dependencies using NPM:

```
npm install
```

Compile TypeScript:

```
npm run build
```

Run server locally:

```
npm start
```

## Experimenting

Navigating to the server URL (logged to output) opens a GraphQL playground, where you can explore the documentation and try executing queries and mutations.

If you wish to try out some code changes, run `npm run dev` and your server will relaunch automatically when you save a file.