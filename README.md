![Build Status](https://img.shields.io/github/workflow/status/GermainMichaud/Food-Order/CI?label=Build&logo=githubactions&logoColor=white&style=for-the-badge)
![React](https://shields.io/badge/-React-grey?logo=react&style=for-the-badge)
![NestJS](https://shields.io/badge/-NestJS-red?logo=nestjs&style=for-the-badge)

# Food Order

This project is a workspace containing an API (NestJS), a web app (React) and a mobile app (React Native).

---

## Content

- [Food Order](#food-order)
  - [Content](#content)
  - [Get Started](#get-started)
  - [Project Structure](#project-structure)
  - [API](#api)
  - [Web App](#web-app)
  - [Mobile App](#mobile-app)
  - [Code Of Conduct](#code-of-conduct)
  - [Contributing](#contributing)
  - [License](#license)

---

## Get started

First you will need to clone the project

```bash
git clone git@github.com:GermainMichaud/Food-Order.git
cd ./Food-Order
```

Next, you have to install dependencies

```bash
npm i # or yarn
```

---

## Project structure

```bash
Todo-Order/
  | apps/
    | api/
    | mobile/
    | mobile-e2e/
    | web/
    | web-e2e/
  | coverage/
  | dist/
  | libs/
  | node_modules/
  | tools/
  | .editorconfig
  | .eslintrc.json
  | .gitignore
  | .prettierignore
  | .prettierrc
  | babel.config.json
  | jest.config.js
  | jest.preset.js
  | nx.json
  | package-lock.json
  | package.json
  | README.md
  | tsconfig.base.json
  | workspace.json
```

For more information, see NX documentation about project structure ([link](https://nx.dev/l/n/getting-started/nx-setup#folder-structure))

---

## API

**Launch server in DEV environment:**

```bash
nx serve api
```

It will start the API at `http://localhost:3333`

**Launch test:**

```bash
nx test api
```

**Build the api:**

```bash
nx build api
```

---

## Web App

**Launch server in DEV environment:**

```bash
nx serve web
```

It will start the dev server at `http://localhost:3000`

**Launch test:**

```bash
nx test web
```

**Build the app:**

```bash
nx build web
```

---

## Mobile App

> Coming...

---

## Todo

- [ ] Write documentation
- [ ] Implement API
  - [ ] ...
- [ ] Implement Web App
  - [ ] ...
- [ ] Dockerize apps

---

# Code Of Conduct

[Read](./CODE_OF_CONDUCT.md)

---

# Contributing

[Read](./CONTRIBUTING.md)

---

# License

[MIT](./LICENSE)
