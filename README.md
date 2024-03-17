# cTodo

English | [简体中文](./.github/README.zh-CN.md)

> Now work in process.
>
> Docs: <https://ctodo.chillcicada.com>

## Introduction

cTodo is a simple extension for chrome/edge and firefox.

## Usage

You can see the usage of this extension in [cTodo Docs](https://ctodo.chillcicada.com/guide).

## Development

**This repo uses `pnpm` as package manager and requires Node version >= 18.** Please make sure you have `node` installed and configured and have `pnpm` installed and enabled.

```bash
# ensure pnpm is enabled
corepack enable
# if you run the below commands crash `pnpm: not found` error you can install pnpm via:
npm install -g pnpm
```

- git clone this repo
- run `pnpm i` to install dependencies
- run `pnpm dev` to start the development server on chrome (**This requires you to have chrome installed**)
  - run `pnpm dev:firefox` to start the development server on firefox (**This requires you to have firefox installed**)
- run `pnpm build` to build the extension for chrome-mv3 (default)
  - run `pnpm build:firefox` to build the extension for firefox

All outputs can be found in the '.output' folder.

For integration test, you need to enable the `developer mode` in your browser and load the extension from the `.output` folder.

More scripts can be found in `package.json` file. And more information about this repo you can find in the [Docs](https://ctodo.chillcicada.com/design).

## Contributing

Here is what you should know before contributing to this repo: [Code Principle](https://ctodo.chillcicada.com/principle).

## LICENSE

The cTodo is licensed under the [MIT](https://mit-license.org) License, but **EXCLUDING any of the following conditions**:

- You are working / have worked for Informatization Office or Information Technology Center of Tsinghua University.
- Your project is funded or supported in any way by an affiliate of Tsinghua University or any other institution associated with Tsinghua University, **including any competitive projects**.
- Your backlink to this project includes / mentions any of the author's(s') privacy information (such as the author's real name, school email, student ID or any other private information).

If any of these criteria is met, any use of code, without **explicit** authorization from the author(s), from this project will be considered as infringement of copyright (and the author's(s') privacy). In addition, if your behavior violates the third criteria, <u>without getting permission</u>, you **must choose to** remove all the relevant privacy information **or** remove the backlink (such as using `[cTodo](link/to/thisProject) Nickname` or `cTodo RealName`).

The word '**use**' may refer to making copies of, modifying, redistributing of the source code or derivatives (such as browser extension) of this project, whether or not for commercial use. However you can still install and run the browser extension released by the author without being constrained by this exception.
