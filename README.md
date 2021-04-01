# Migration of Express.js Application from JavaScript to TypeScript

This repo shows the differences between a javascript, and typescript setup of an express application.
Starting from pure javascript/typescript, to node.js, and finally with express.js

## JavaScript Setup

To work with javascript no speciffic setup is needed.
You can just go:

```javascript
const hello = "Hello World!";
console.log(hello);
```

But if you want to execute any javascript code outside of a browser, you have to install nodejs

## TypeScript Setup

With typescript you could just do the same.

```typescript
const hello: string = "Hello TypeScript";
console.log(hello);
```

But before you can execute it you have to transpile it to javascript.
If you are using vscode the typescript compiler is already integrated.
That means you can use the tsc command:

```bash
tsc <filename>
```

this will transpile your typescript file to javascript.

In case you don't use vscode you have to install the typescript package as devdependency.

```bash
npm install -D typescript
```

this package is also needed for some other pakages that are working with typescript.
Because of that it it safer to install it if you want to develop an application with typescript.

## JavaScript and Node Setup

## TypeScript and Node Setup

## JavaScript and Express Setup

## TypeScript and Express Setup
