# funda [![npm version](https://badge.fury.io/js/funda.svg)](https://badge.fury.io/js/funda)
## Installation
You can either run `funda` with `npx`:

```bash
npx funda
```

or you can install `funda` globally

```
npm i -g funda
```

## Usage
Runing `funda` creates a project for your future λ function.

It has a certain project structure and uses certain libraries.

Created λ function depends on following packages:
* `shawerma` - https://www.npmjs.com/package/shawerma
* `serverless-offline` - https://www.npmjs.com/package/serverless-offline
* `serverless-jest-plugin` - https://www.npmjs.com/package/serverless-jest-plugin

Once your project is created you can `cd` into the newly created folder and
run `npm start` to run your λ function locally.

Running `npm test` will run your tests with `jest`
