# angular2-webpack

[![Dependency Status](https://david-dm.org/preboot/angular2-webpack/status.svg)](https://david-dm.org/preboot/angular2-webpack#info=dependencies) [![devDependency Status](https://david-dm.org/preboot/angular2-webpack/dev-status.svg)](https://david-dm.org/preboot/angular2-webpack#info=devDependencies)
[![Join the chat at https://gitter.im/preboot/angular2-webpack](https://badges.gitter.im/preboot/angular2-webpack.svg)](https://gitter.im/preboot/angular2-webpack?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

**Note: This guide is following the Angular's [Style Guide](http://angular.io/styleguide) so I will be changing conventions here and there eventually. You are free to use your own conventions with this starter.**
**Note 2: There is no conventions yet for RC5 on the style guide so there will be a future update here for that.**

A complete, yet simple, starter for Angular 2 using Webpack.

This seed repo serves as an Angular 2 starter for anyone looking to get up and running with Angular 2 and TypeScript fast. Using [Webpack](http://webpack.github.io/) for building our files and assisting with boilerplate. We're also using Protractor for our end-to-end story and Karma for our unit tests.
* Best practices in file and application organization for [Angular 2](https://angular.io/).
* Ready to go build system using [Webpack](https://webpack.github.io/docs/) for working with [TypeScript](http://www.typescriptlang.org/).
* Testing Angular 2 code with [Jasmine](http://jasmine.github.io/) and [Karma](http://karma-runner.github.io/).
* Coverage with [Istanbul](https://github.com/gotwarlost/istanbul)
* End-to-end Angular 2 code using [Protractor](https://angular.github.io/protractor/).
* Stylesheets with [SASS](http://sass-lang.com/) (not required, it supports regular css too).
* Error reported with [TSLint](http://palantir.github.io/tslint/) and [Codelyzer](https://github.com/mgechev/codelyzer).
* Documentation with [TypeDoc](http://typedoc.io/).

### Quick start

> Clone/Download the repo then edit `app.ts` inside [`/src/app/app.component.ts`](/src/app/app.component.ts)

```bash
# clone the repo
$ clone https://github.com/Ad4mJ/angular2-webpack.git my-app

# change directory to your app
$ cd my-app

# install the dependencies with npm
$ npm install

# start the server
$ npm start
```
go to [http://localhost:8080](http://localhost:8080) in your browser.

# Table of Contents

* [Getting Started](#getting-started)
    * [Dependencies](#dependencies)
    * [Installing](#installing)
    * [Developing](#developing)
    * [Testing](#testing)
    * [Production](#production)
    * [Documentation](#documentation)
* [Frequently asked questions](#faq)
* [TypeScript](#typescript)
* [License](#license)

# Getting Started

## Installing

* `git clone https://github.com/Ad4mJ/angular2-webpack.git` this repo
* `npm install` to install all dependencies

## Developing

After you have installed all dependencies you can now start developing with:

* `npm start`

It will start a local server using `webpack-dev-server` which will watch, build (in-memory), and reload for you. The application can be checked at `http://localhost:8080`.

## Testing

#### 1. Unit Tests

* single run: `npm test`
* live mode (TDD style): `npm run test-watch`

#### 2. End-to-End Tests (aka. e2e, integration)

* single run:
  * in a tab, *if not already running!*: `npm start`
  * in a new tab: `npm run webdriver-start`
  * in another new tab: `npm run e2e`
* interactive mode:
  * instead of the last command above, you can run: `npm run e2e-live`
  * when debugging or first writing test suites, you may find it helpful to try out Protractor commands without starting up the entire test suite. You can do this with the element explorer.
  * you can learn more about [Protractor Interactive Mode here](https://github.com/angular/protractor/blob/master/docs/debugging.md#testing-out-protractor-interactively)

## Production

To build your application, run:

* `npm run build`

You can now go to `/dist` and deploy that to your server!


### Tech Used

| **Tech** | **Description** | **Version** |
| ---------|-----------------|-------------|
| [Angular2](https://facebook.github.io/react/) | View layer | 2.0.0-rc.5 |
| [Angular Router](https://github.com/reactjs/react-router) | Universal routing | 3.0.0-rc.1 |
| [Redux](http://redux.js.org/) | State management | 3.5.0 | Not Yet Implemented
| [WEBAPI](http://www.asp.net/web-api) | Persistance layer | 2.3.1 |
| [Express](http://expressjs.com/) | Node.js server framework | 4.13.0 |
| [SignalR]() | Used for realtime communication between clients and server | 1.4.0 |
| [Webpack](https://webpack.github.io/) | Module bundling + build for client | 1.13.0 |
| [Superagent](https://github.com/visionmedia/superagent) | Universal http requests | 1.8.0 |
| [Stylus](http://stylus-lang.com/) | Expressive, dynamic, robust CSS | 0.54.0 |




