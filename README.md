# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```sh
npm install --save-dev @kdt-js/tsconfig
```

*This config requires TypeScript 5 or later.*

## Usage

`tsconfig.json`

```jsonc
{
    "extends": "@kdt-js/tsconfig",
    "compilerOptions": {
        // ...
    }
}
```

* For [Vue](https://vuejs.org), extend `@kdt-js/tsconfig/vue` instead.

* For building a library, using `@kdt-js/tsconfig/lib` and specify `outDir` in your `tsconfig.json`.
