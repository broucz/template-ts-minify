# template-ts-minify

Minimal boilerplate that compiles Typescript into a minifyed CommonJS file.

Example:

Input:

```ts
(function() {
  let my_var = 'Hello';
  alert(my_var);
})();
```

Output:

```ts
(function(){alert("Hello")})();
```

## Setup

```
git clone git@github.com:broucz/template-ts-minify.git
cd template-ts-minify
npm install
```

## Build

```
npm run build
```
