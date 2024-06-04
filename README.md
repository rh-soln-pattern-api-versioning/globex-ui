# GlobexUi

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.5.
This also has "Server-side rendering (SSR) with Angular Universal" enables. Read more about this here: https://angular.io/guide/universal

## Running on Server Side

Run `npm run dev:ssr` for running this as server side app. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build docker image

podman build . -t quay.io/rh_soln_pattern_api_versioning/globex-ui:<version>

## Push docker 

podman push quay.io/rh_soln_pattern_api_versioning/globex-ui:wip