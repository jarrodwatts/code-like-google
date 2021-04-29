# Next.JS Style Guide: Google Edition

## This project is a guide for creating new Next.JS projects using Google's TypeScript Style guidelines.

<br>

### Technologies we are using:

- ESLint ([`.eslintrc.js`](./.eslintrc.js))
- Prettier ([`.prettierrc`](./.prettierrc))
- Typescript ([`tsconfig.json`](./tsconfig.json))
- `eslint-config-prettier` (helps eslint and prettier get along)

### Auto-formatting on save:

Inside `/.vscode/settings.json` we set prettier as the default formatter, and also set `editor.codeActionsOnSave` to run:

- **Lint:** `"source.fixAll.eslint"`
- **Format:** `"source.fixAll.format"`

### Checking standards pre-commit:

Using [husky](https://www.npmjs.com/package/husky) we can check all of our style standards to make sure our git commits are up to par. Check those checks out at [`.husky/pre-commit`](.husky/pre-commit)
