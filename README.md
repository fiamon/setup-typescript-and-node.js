## Functionalities

- Jest setup and configs
- TypeScript setup and configs
- Husky setup and configs (will perform certain actions when you commit)
- ESLint with Prettier


## Instalation

This is a quick setup for projects with Node.js and TypeScript

Before installing, [download and install Node.js](https://nodejs.org/en/download/). 
Node.js 18 or higher is required.

To start the installation, you must clone this repository.

```shell
git clone https://github.com/fiamon/setup-typescript-and-node.js.git
```

After that, install the **development** dependencies.

NPM:
```shell
npm install 
```
YARN: 
```shell
yarn
```
You must run the following command to set husky on:

NPM:
```shell
npx husky:prepare 
```
YARN: 
```shell
yarn husky:prepare
```
