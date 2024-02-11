# AmplifyLogin

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.0.5.

## Make auth work

We need to do a few things to get this:

- Run "amplify init"
- Run "amplify import auth". In this step, you can select the cognito pool that is created on your account
- Run "amplify push" for update the changes

### Related information:
- https://docs.amplify.aws/angular/start/project-setup/prerequisites/
- https://docs.amplify.aws/angular/build-a-backend/auth/set-up-auth/
- Backend project for create and configuring user pools -> https://github.com/Rollerf/cognito-api-login/tree/feat/aws-amplify

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
