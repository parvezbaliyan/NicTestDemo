# Requirements

You need [Node](https://nodejs.org/en/). And that's it.

I'm using Babel to run ES2015. :heart: So don't worry, you won't have to read ES5 code.


# Instructions tu Run This

- `npm install` to create a folder full of the most outlandish dependencies.
- `npm run test` will run tests.
- `npm start [filename]` would start a ES7 running version of the code, but we do need to transpile to ES5 for a clean
output.
- `npm run build` will compile to ES5.
- `node dist/index input.txt` is all you need to run the optimizes version of the project. Of course `input.txt` is the
route of your file will run the code and return a clean output.
- If something explodes, don't worry. It's part of the masterplan.

# The Code
- `src` has all the sourcefiles.
- `test` has all the tests.
- `src/index.js` is the entry point of the app.
