This repository demonstrates a common but easily overlooked error in TypeScript: not handling optional properties correctly.  The `bug.ts` file contains code that will fail if an object missing either an `x` or `y` property is passed to the `printCoord` function. The `bugSolution.ts` demonstrates a solution using optional chaining and nullish coalescing.