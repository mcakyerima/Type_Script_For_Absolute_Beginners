# ﻿Introduction to TypeScript:

TypeScript is a superset of JavaScript that transpiles to JavaScript code at runtime and executes it. It utilizes ECMAScript 5 (ES5) under the hood, which is a long-term version of JavaScript.

Key Concepts:

1. **Setting up TypeScript Configuration:**
   - Use `tsc --init` to create a TypeScript configuration file named `tsconfig.json`.
   - In the `tsconfig.json` file, you can specify the target ECMAScript version using the `"target"` property. For example, you can change it from `"target": "ES2016"` to `"target": "ES2023"` by deleting "2016" and pressing Ctrl + Space.
   
2. **Configuration Options:**
   - `rootDir`: Specifies the root directory of our project. This is typically set to `./app` or `./src`.
   - `outDir`: Specifies the directory where the TypeScript compiler will emit JavaScript code. By convention, we set this to `./dist`, which is a distributable folder.
   - `onEmit`: By default, even if there is an error in our TypeScript code, the compiler still generates JavaScript code. Setting this to `true` will stop the compiler from compiling if there is an error.
   
3. **Source Map Feature:**
   - TypeScript provides a source map feature, which is a file that specifies how each line of our TypeScript code maps to the generated JavaScript code. This feature aids in debugging and understanding the relationship between TypeScript and JavaScript code.

By understanding and configuring these key concepts, you can effectively leverage TypeScript in your projects to enhance type safety and maintainability.
