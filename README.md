# tsconfigs

Opinionated `tsconfig.json` files used for Typescript projects. 

# Getting started 

* Install the config files into your project:

```
npm install --D @levibostian/tsconfigs
```

* Use the tsconfig file that you wish in your project:

```json
{
    "extends": "@levibostian/tsconfigs/node12/tsconfig.json"
}
```

* That's it! If you want to override anything from the base config, feel free to add config options to your tsconfig file. 

# node14

tsconfig designed for nodejs 14 projects. Based off of [community tsconfig base](https://www.npmjs.com/package/@tsconfig/node14) with my own changes. 

# node12 

tsconfig designed for nodejs 12 projects. Based off of [community tsconfig base](https://www.npmjs.com/package/@tsconfig/node12) with my own changes. 

# Contributing 

I am always open to collaboration, questions, and help on projects. However, this project is opinionated for projects that I develop. I may not accept pull requests into this project. 