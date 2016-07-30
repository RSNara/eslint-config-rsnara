# eslint-config-rsnara

A base `.eslintrc` containing the set of rules I like to use for my JavaScript projects.

## Installation
```BASH
npm install eslint-config-rsnara eslint --save-dev
```

## Usage
For new projects, the following should suffice:
```BASH
echo '{\n  "extends": "rsnara"\n}' > ./.eslintrc
```

For more details, please read the eslint docs on [Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs).

## Dependencies
- [babel-eslint](https://github.com/babel/babel-eslint)
- [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react)
- [eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable)
