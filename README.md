<<<<<<< HEAD
# YacsWeb

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
=======
# YACS Orchestra

The purpose of this repository is to aid in the development and deployment of YACS and it's dependencies.

## Prerequisites

This is your entry point as a YACS developer. To get started developing or deploying, follow these instructions.

If you have not used git or Github before, make sure your local git name and email are set, and you have your SSH key uploaded to Github.
Follow these [instructions](https://help.github.com/articles/set-up-git/) from Github. Please use SSH instead of HTTPS.

Please install [Docker](https://www.docker.com/community-edition) and [docker-compose](https://docs.docker.com/compose/install/).
It is recommended to use either Linux or macOS.

If you use Linux, it is recommended to follow the [post-installation](https://docs.docker.com/install/linux/linux-postinstall/)
sections "Manage Docker as a non-root user" and "Configure Docker to start on boot".

Running YACS on Windows may be possible, but it is not recommended and not supported.

## Development

1. Clone this repository
  `git clone git@github.com:YACS-RCOS/yacs-orchestra.git`

2. Enter the cloned directory
  `cd yacs-orchestra`

3. Run the one-time setup script
  `bin/yacs-setup-development`

You can now use the following command to run YACS:
  `bin/yacs-start-development`

To stop YACS, press ctrl+c and run the following command
  `bin/yacs-stop-development`

>>>>>>> 121487619267cdc006d1f8bcacb7a44679642802
