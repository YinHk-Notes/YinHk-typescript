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
npm install typescript --save-dev
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

