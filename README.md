### Node ES6 Babel Boilerplate

Boilerplate for npm projects requiring Babel ES6 transpilation (includes babel-cli).

#### Installation

Run `npm install` to create the boilerplate project. This installs babel-core, babel-cli and babel-preset-es2015 for the actual ES6 transpilation.

The package builds each file from /src to /lib but this is easy enough to change in package.json. See https://babeljs.io/docs/usage/cli/ for more information on the Babel command line options

#### Building

Run `npm run build` to build once, or `npm run watch` to build on each change.
