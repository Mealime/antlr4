
## TypeScript / NPM compatible fork of the JavaScript runtime

- Type definitions pulled from https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/antlr4
- Copies JavaScript sources at build time
- Replaces index.js with more minimal version without requiring `fs`
- Transpiles down the class types for compatibility
- Keeps to the old antlr <=4.8 NPM package directory structure