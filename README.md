# Developing Javascript - getting started with Node.js and NPM

- uses `vscode` with the `remote - containers` plugin
- remote containers is configured to use the `node` docker image

Further reading:
- node.js standard library: https://nodejs.org/api/

## Plain node.js

A simple script `app.js` can be run on the command line (no dependencies, no building or bundling).

## Bundling with webpack

Run `npm install --save-dev webpack webpack-cli`

As usual, `npm` will create or update following files:
- `package.json` (refering to `webpack` only)
- `package-lock.json` (refering to `webpack` and its seventy-or-so dependencies)
- `node_modules` (containing the downloaded packages)

Manually create or update `webpack.config.js`.

Finally, in `package.json`, section `scripts`, add a `build` directive to run `webpack`.
With that, `npm run build` will execute `webpack`.
