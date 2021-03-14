[![npm version](https://img.shields.io/npm/v/@levibostian/tsconfigs.svg?style=flat-square)](https://www.npmjs.org/package/@levibostian/tsconfigs)

# tsconfigs

Opinionated `tsconfig.json` files used for Typescript projects. 

# Getting started 

* Install the config files into your project:

```
npm install --D @levibostian/tsconfigs
```

* Edit your project's `tsconfig.json` file to extend one of the bases of this project. 

*Note: There are some config options in your `tsconfig.json` that a base config file cannot support. Some of those have been documented in the code sample below so make sure that you include those.*

```json
{
  "extends": "@levibostian/tsconfigs/node14/tsconfig.json",
  "compilerOptions": {
    "outDir": "dist",
    "paths": {
      "*": ["node_modules/*", "@types/*"]
    },
    "typeRoots": ["@types", "./node_modules/@types"]
  },
  "include": ["app/**/*", "@types/**/*"]
}
```

*Tip: It's recommended you run `npx tsc` in your project after setting up your `tsconfig.json` file changes to make sure it's working as you expect. 

* That's it! If you want to override anything from the base config, feel free to add config options to your tsconfig file. 

# node14

tsconfig designed for nodejs 14 projects. Based off of [community tsconfig base](https://www.npmjs.com/package/@tsconfig/node14) with my own changes. 

# node12 

tsconfig designed for nodejs 12 projects. Based off of [community tsconfig base](https://www.npmjs.com/package/@tsconfig/node12) with my own changes. 

# Contributing 

I am always open to collaboration, questions, and help on projects. However, this project is opinionated for projects that I develop. I may not accept pull requests into this project. 