# Hungry Hippo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.3.
It contains the source code for online ordering of food from local homes.

## Before you begin

Perform the following steps:

1. Make sure you have the latest version of [Node.js][node] installed. This also contains **npm**, a package manager. 
If on Linux or Mac OS, we recommend using a tool like [NVM][nvm] (Linux) or [HomeBrew][brew] (macOS), which allows you to swap between installed versions of Node.
2. If using IntelliJ, ensure your JavaScript language version is set to ECMAScript 6.
3. Install the Angular CLI:
  ```bash
  npm install -g @angular/cli
  ```
4. Clone this repository.

### Install your dependencies

Run the following command in the same directory as the **package.json** file, to install all required dependencies for the project:
```bash
npm install
```

### (Optional) Alternative dependency managers

You can alternatively use [Yarn][yarn], which is a (super) fast package manager with some very nice features:
```bash
yarn install
```

If you choose to use yarn, set it as your default package manager for the Angular CLI:
```bash
ng set --global packageManager=yarn
```

We highly-recommended to checking in the generated **yarn.lock** file.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.
Use `ng build -prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma][karma].

Run `ng test --code-coverage` for code coverage

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor][protractor].
Before running the tests make sure you are serving the app via `ng serve`.

## Deploying with Docker

First make sure you have [Docker CE][docker] installed.

Run `ng build -prod` to generate a production build, which will end up in a new `/dist` directory.

Run the following to generate a Docker image, including the static build files:
```bash
docker build -t node-expansion-ui-image .
```

Run the generated Docker image, with port mapping to the host
```bash
docker run --name node-expansion-ui -d -p 8080:80 node-expansion-ui-image
```

Open http://localhost:8080/ on your browser.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README][angular-readme].

[angular-readme]: https://github.com/angular/angular-cli/blob/master/README.md
[node]: https://nodejs.org/en/download/
[brew]: https://brew.sh/
[nvm]: https://github.com/creationix/nvm#installation
[yarn]: https://yarnpkg.com/lang/en/docs/install/
[docker]: https://store.docker.com/editions/community/docker-ce-desktop-windows/
[protractor]: http://www.protractortest.org/
[karma]: https://karma-runner.github.io
