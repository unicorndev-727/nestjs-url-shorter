# NestJS MongoDB URL Shortener

A URL shortener server-side app built with [Nest.js](https://nestjs.com/) and [MongoDB](https://www.mongodb.com/).

## Quick Start

1. Install [Node.js](https://nodejs.org/en/download/) - _for IDE type checking_.
2. Install [Yarn](https://yarnpkg.com/lang/en/docs/install/) - _for IDE type checking_.
3. Install [Docker Compose](https://docs.docker.com/compose/install/).
4. Clone the app:

```bash
git clone git@github.com:unicorndev-727/nestjs-url-shortener.git
```

5. Install npm packages - _for IDE type checking_.

```bash
cd nestjs-url-shortener
yarn install --frozen-lockfile
```

6. Build and run the Docker image.

```bash
yarn docker-compose:dev
```

7. Access the app at http://localhost:3000.
8. Make file changes and it will automatically rebuild the app.

## Running All Tests

```bash
yarn docker-compose:test
```

## Running All Tests (with coverage)

```bash
yarn docker-compose:test:cov
```

## Running Tests (Watch)

1. Build and run the Docker image.

```bash
yarn docker-compose:test:watch
```

2. Make file changes and it will automatically rerun tests related to changed files.

## Build For Production

```bash
yarn docker-compose:prod
```

## VSCode Extensions

- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
