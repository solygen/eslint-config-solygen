# eslint-config-solygen

This package provides solygen's .eslintrc as an extensible shared config.

## Usage

We export two ESLint configurations for your usage.

### eslint-config-solygen

Our default export contains all of our ESLint rules.

1. `npm install --save-dev eslint-config-solygen eslint`
2. add `"extends": "solygen"` to your .eslintrc

### eslint-config-solygen/base

Currently a simple alias for ``eslint-config-solygen``.
1. `npm install --save-dev eslint-config-solygen`
2. add `"extends": "solygen/base"` to your .eslintrc

