# Introduction

salt-pass is a lightweight npm package for securely salting and hashing passwords in Node.js applications. It provides functions for generating random salts and hashing passwords using the SHA-256 algorithm, enhancing the security of password storage.

# Installation

`npm install salt-pass`

# Usage

## Generating a Salt

To generate a random salt, you can use the `generateSalt` function:

```js
const saltPass = require('salt-pass');
const salt = saltPass.generateSalt();

```

## Hashing a Password

To hash a password using a salt, you can use the `hashPassword` function:

```js
const saltPass = require('salt-pass');

const password = 'mySecurePassword';
const salt = 'randomSalt'; // Replace 'randomSalt' with a generated salt
const hashedPassword = saltPass.hashPassword(password, salt);

```

# Contributing

Contributions are welcome! If you encounter any bugs, have feature requests, or want to contribute enhancements or fixes, please feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/Shushant-Priyadarshi/salt-pass-NPM-package).






