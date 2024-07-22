* `deno run main.ts` work
* and the chain of `tsc main.ts` --> `node main.js` doesnt
* we need to not comile default tsc which is es3 and commonjs but `tsc --module nodenext main.ts` !!! opr provide tsconfig like twe did in the last commit
