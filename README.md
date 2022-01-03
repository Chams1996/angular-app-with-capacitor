# AngularAppWithCapacitor

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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

## Generate APK
1. In the **root** of the project **run** the following commands:
   * `ng build --prod`
   * `npx cap copy android`
   * `cd android && ./gradlew assembleDebug && cd ..`
2. In the folder `android/app/build/outputs/debug` you can find your **file.apk**   

## Run App on Android Device
1. Connect your Android device to the PC
2. In the **root** of the project **run** the following commands:
   * `ng build --prod`
   * `npx cap copy android`
   * `cd android && ./gradlew assembleDebug && ./gradlew installDebug && cd ..`
