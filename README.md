# API Template

This project is a template for creating a new API based on [Express](https://expressjs.com/).

[ESLint](https://eslint.org/), [prettier](https://prettier.io/), [husky](https://typicode.github.io/husky/) and [lintstaged](https://github.com/okonet/lint-staged) are configured to give you a solid development experience.

## Installing / Developing

First, [create a repository from this template](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/creating-a-repository-from-a-template).

Now you are ready to go:

```shell
npm install --no-save
```

This will install the dependencies required to run this project.

```shell
npm run dev
```

Boom! These scripts run your server in development mode.

## Building

To build the project in the `/dist` folder, run:

```shell
npm run build
```

The production optimized project is runnable with:

```shell
npm start
```

## Tests

A test runner is not installed (right now). But TypeScript, linter and prettier are checked on commit and push thanks to husky and lintstaged.

## Licensing

MIT
