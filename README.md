# Developing Javascript - getting started with Node.js and NPM

- uses `vscode` with the `remote - containers` plugin
- remote containers is configured to use the `node` docker image

Further reading:
- node.js standard library: https://nodejs.org/api/

## Plain node.js

A simple script `app.js` can be run on the command line (no dependencies, no building or bundling).

## Bundling with webpack

Run `npm install webpack`. As usual, `npm` will create or update following files:
- `package.json` (refering to `webpack` only)
- `package-lock.json` (refering to `webpack` and its fifty-or-so dependencies)
- `node_modules` (containing the downloaded packages)

Manually create or update `webpack.config.js`
