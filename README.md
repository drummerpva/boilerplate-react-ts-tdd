#BoilerPlate ReactJS TS

- Message Linter /_Garante que os commits serão dentro do padrão [conventional](https://www.conventionalcommits.org/en/v1.0.0/#specification) _/

  - <code> npm i -D git-commit-msg-linter</code>

- TypeScript /_Usar o tsconfig.json como base_/

  - <code>npm i -D typescript @types/node</code>

- Linter /_Usar o .eslintrc.json e .eslintignore como base_/
  - <code>npm i -D eslint eslint-config-standard-with-typescript eslint-plugin-import eslint-plugin-promise eslint-plugin-node @typescript-eslint/eslint-plugin</code>

###Git Hooks

- Garantir que o código esteja formatado corretamente antes do commit/_Usar .lintstagedrc.json e .huskyrc.json como base_/
  - <code>npm i -D lint-staged husky</code>
