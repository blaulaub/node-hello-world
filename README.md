# Developing Angular - getting started with Node.js and NPM

Requires Node.js, npm, ng-cli.
- either have these installed locally
- or use `vscode` with the `remote - containers` plugin, see [.devcontainer/README.md](.devcontainer/README.md)

Further reading:
- Angular setup: https://angular.io/guide/setup-local
  - in addition, the project installs 'its' version of angular locally during `npm install`
- node.js standard library: https://nodejs.org/api/

## Getting started with Angular

Angular-CLI wants to create the workspace itself by `ng new <name>`.

There will be the usual `npm` files and directories:
- `package.json`
- `package-lock.json`
- `node_modules` (containing the downloaded packages)

Angular adds some more configuration:
- `.browserlistrc` for browser compatibility
- `angular.json` for Angular app configuration
- `karma.conf.js` as test runner
- `tsconfig.json`, `tsconfig.app.json` and `tsconfig.spec.json`

The following information is also written by Angular to the README.md:

## Angular README

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.7.

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
