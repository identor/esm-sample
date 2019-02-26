# Proof of Concept: Using esmodules without babel
This repository uses `esmodules` standard without transpilation thru the use of [`esm`](https://npmjs.com/package/esm). The repository contains sample usage for running regular nodejs programs see `main.js`, and test files `main.spec.js`.

To enable es modules, here are the steps performed:

1. Install `esm`
2. Add `esm` field in `package.json`
3. Run `mocha` or `node` with `-r` flag, this requires esm.
