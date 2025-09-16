# React + Vite template

## Toolchain

- Language: [TypeScript](https://www.typescriptlang.org/)
- Package manager: [pnpm](https://pnpm.io/)
- CSS Framework: [TailwindCSS](https://tailwindcss.com/)
- Linter: [ESLint](https://eslint.org/)
- Formatter: [Prettier](https://prettier.io/)
- Testing: [jest](https://jestjs.io/)
- Automatic class sorting:
  [prettier-plugin-tailwindcss](https://tailwindcss.com/blog/automatic-class-sorting-with-prettier)
- Pre-commit checks for the following:
  - [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
  - Prettier
  - ESLint

## Setup

1. Clone this repository
2. Install the pre-commit hooks:

```bash
pre-commit install --install-hooks
```

3. Install packages:

```bash
pnpm install
```

4. Change `name` property in package.json to your project name:

```json
{
  "name": "<your-project-name>"
}
```
