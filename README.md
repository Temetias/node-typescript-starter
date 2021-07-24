# Simple Node.js + TypeScript starter

A minimimalistic template to get started with a [node.js](https://nodejs.org/) project with [TypeScript](https://www.typescriptlang.org/). Unopinionated and simple, only featuring build scripts, entry point, ignore files and a standard prettier setup.

## Get started:

#### Mandatory

- `npm install && npm start` (to install dependencies and start development server)

#### Optional

- Change project and author names from `package.json`
- `rm -rf .git && git init` (fresh version control)
- Setup format on save for [prettier](https://prettier.io) ([Check guide for your editor here.](https://prettier.io/docs/en/editors.html))

## Features

- [TypeScript](https://www.typescriptlang.org/)
- Dev server scripts via `npm start` and `npm run dev`, these 2 commands are functionally the same
- Build script via `npm build`, builds solution to `/dist` folder.
- Standard [prettier](https://prettier.io) config
- Ignore files based on https://github.com/github/gitignore/blob/master/Node.gitignore

## Notes

- Override default [prettier](https://prettier.io) configuration by [using the .prettierrc.json file](https://prettier.io/docs/en/configuration.html)
- Build directory is `/dist`, if you wish to change it, check both `tsconfig.json` and `package.json`
- If you don't want your entry point being `index.ts` and `index.js`, you can change them BUT remember to also check the scripts in `package.json` to match your new name

## Contributing

Repo is open for contribution. Accepted PR's include improvements, bug fixes, documentation, generalization, cross platform improvements, version changes, etc.

PR's aiming to add more opinions and features will be rejected for the sake of simplicity.
