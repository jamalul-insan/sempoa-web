## Sempoa Web

Homepage of sempoa.id and billing management or user panel.

## Installation

- clone the project
- `cd` into the project folder
- `cp .env.example .env` and preserve your empty database
- `npm install` or `yarn install` or `bun install` or `pnpm install` to install dependencies
- `node ace serve --watch` to run, default: **localhost:3333**

## Shortcuts

`mfs` = node ace migration:fresh --seed

`migrate` = node ace migration:run

`routes` = node ace list:routes

usage: `npm run routes` or `yarn routes`
