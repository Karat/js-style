# js-style

Shareable ESLint config

## Install

```
yarn add --dev ssh://git@github.com:Karat/js-style.git#<LATEST_GITHUB_COMMIT_NUMBER>
yarn add --dev babel-eslint eslint
```

Note: You can get the latest Github commit by clicking on [commits](https://github.com/Karat/js-style/commits/master).

## Use

Extend in your project [eslint config](https://eslint.org/docs/user-guide/configuring#using-a-shareable-configuration-package):

```
// .eslintrc.yml
extends:
  - js-style
```

Note: This is not necessary if using sapphire to run the linter tasks.

## Run

See the [Getting Started with ESLint](https://eslint.org/docs/user-guide/getting-started) guide.
