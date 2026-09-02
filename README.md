# NestJS Notifications Service

A notifications API built during Ignite Lab to practice NestJS, Prisma and automated testing.

## Project goal

Implement a small but complete notification domain while learning how NestJS modules, controllers and providers fit around application use cases.

## Features

- Create notifications
- Read and unread state transitions
- Cancel notifications
- Persist data with Prisma
- Unit and end-to-end tests

## Technologies

- **TypeScript**
- **Node.js**
- **NestJS**
- **Prisma**
- **Jest**
- **Supertest**

## What I learned

- Organizing a NestJS application into modules and providers
- Modeling notification behavior as use cases
- Testing application rules independently
- Connecting HTTP controllers to persistence

## Running locally

```bash
npm install
npx prisma generate
npm run start:dev
```

## Project status

This is a learning project and is not presented as a production-ready application.
