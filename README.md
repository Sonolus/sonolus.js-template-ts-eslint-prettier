# Sonolus.js Template (TS + ESLint + Prettier)

## Prerequisites

-   [Node.js](https://nodejs.org)

## Recommended Setup

-   [Visual Studio Code](https://code.visualstudio.com)
-   [ESLint extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

## Get Started

To get this template, run (change `my-project` to desired name):

```
npx degit Sonolus/sonolus.js-template-ts-eslint-prettier my-project
```

To install dependencies, run in project directory:

```
npm i
```

## Start Dev Server

Run in project directory:

```
npm run dev-play
```

```
npm run dev-watch
```

```
npm run dev-preview
```

```
npm run dev-tutorial
```

A dev server will be up and running. You can connect to it using Sonolus app and play test the level.

Changes made to the project will be automatically detected and trigger rebuild.

Temporary files and extraction artifacts can be found in `.dev`.

## Check for Issues

Run in project directory:

```
npm run check-type
```

```
npm run check-lint
```

```
npm run check-format
```

## Fix Issues

Run in project directory:

```
npm run fix-lint
```

```
npm run fix-format
```

## Build

Run in project directory:

```
npm run build
```

Build artifacts can be found in `dist`.
