# eslint-config

> Write consistency JavaScript without losing your brain

[![npm](https://img.shields.io/npm/v/@chtijs/eslint-config.svg?maxAge=2592000)](https://www.npmjs.com/package/@chtijs/eslint-config)
[![Build Status](https://travis-ci.org/ChtiJS/eslint-config.svg?branch=master)](https://travis-ci.org/ChtiJS/eslint-config)

## Installation

```bash
npm install @chtijs/eslint-config --save-dev
```

## Usage

In your `.eslintrc`:

```json
{
  "extends": "@chtijs"
}
```

## Overview

Extends the default eslint config, parses with Babel, and adds the `import` plugin. Includes these hot rules:

- Two spaces for indentation.
- Single quotes.
- More rigit JSDoc enforcement.
- Allow functions to be defined after they're first referenced. (Yay hoisting!)
- `if`/`else` go on separate lines.
- Consistent return values optional.
- Prefer `const`, then `let`, but never `var`.
- Capitalize the first word in a comment.
- Put spaces around inline objects.
- Always use `===` and `!==`.
- Class methods must use `this` (otherwise they can be static).

## Local Development

```bash
git clone https://github.com/chtijs/eslint-config
cd eslint-config
```

## License

MIT &copy; Hacked from [Geoff Kimball](http://geoffkimball.com)
