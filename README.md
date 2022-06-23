## YinHk-TypeScript
TypeScript cheatsheet and notes
-- --
#### What is TypeScript?
- TypeScript is JavaScript with syntax for types,  and some additional features like generics, interface etc.
- TypeScript is a typed superset of JavaScript that compiles to plain JavaScript. 
- TypeScript is a Object-Oriented programming.
- TypeScript Code is converted into Plain JavaScript Code:
 TypeScript code can’t be natively interpreted by browsers. So if the code was written in TypeScript, it gets compiled and converted into JavaScript before execution.

#### use typescript

via npm

```
npm install -g typescript
```

```
npm install typescript --save-dev
```

```tsx
npx tsc --init        # generate tsconfig.json
```

#### Compile and Execute a TypeScript Program
```tsx
npx tsc index.ts 
```
After compiled, it will change to js file, then execute the js file by nodejs
```tsx
$ node index.js
```
Note − Multiple files can be compiled at once:
```tsx
tsc file1.ts, file2.ts, file3.ts
```

**ts-node**
ts-node is a TypeScript execution engine and REPL for Node.js.
```
# Execute a script as `node` + `tsc`.
ts-node script.ts
```

#### TS playground
https://www.typescriptlang.org/play?#code/PTAEHUFMBsGMHsC2lQBd5oBYoCoE8AHSAZVgCcBLA1UABWgEM8BzM+AVwDsATAGiwoBnUENANQAd0gAjQRVSQAUCEmYKsTKGYUAbpGF4OY0BoadYKdJMoL+gzAzIoz3UNEiPOofEVKVqAHSKymAAmkYI7NCuqGqcANag8ABmIjQUXrFOKBJMggBcISGgoAC0oACCbvCwDKgU8JkY7p7ehCTkVDQS2E6gnPCxGcwmZqDSTgzxxWWVoASMFmgYkAAeRJTInN3ymj4d-jSCeNsMq-wuoPaOltigAKoASgAywhK7SbGQZIIz5VWCFzSeCrZagNYbChbHaxUDcCjJZLfSDbExIAgUdxkUBIursJzCFJtXydajBBCcQQ0MwAUVWDEQC0gADVHBQGNJ3KAALygABEAAkYNAMOB4GRonzFBTBPB3AERcwABS0+mM9ysygc9wASmCKhwzQ8ZC8iHFzmB7BoXzcZmY7AYzEg-Fg0HUiQ58D0Ii8fLpDKZgj5SWxfPADlQAHJhAA5SASPlBFQAeS+ZHegmdWkgR1QjgUrmkeFATjNOmGWH0KAQiGhwkuNok4uiIgMHGxCyYrA4PCCJSAA

