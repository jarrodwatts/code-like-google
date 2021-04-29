# Next.JS Style Guide: Google Edition

## This project is a guide for creating new Next.JS projects using Google's TypeScript Style guidelines.

<br>

### Technologies we are using:

- ESLint (`.eslintrc.js`)
- Prettier (`.prettierrc`)
- Typescript (`tsconfig.json`)
- `eslint-config-prettier` (helps eslint and prettier get along)

<br>

### Auto-formatting on save:

Inside `/.vscode/settings.json` we set prettier as the default formatter, and also set `editor.codeActionsOnSave` to run:

- **Lint:** "source.fixAll.eslint"
- **Format:** "source.fixAll.format"
