# AngularMISC

Required:
- Node.js
- npm

Checking installed versions in system command line:
- node -v
- npm -v
- ng version (Angular CLI)

Installing Angular CLI globally:
- npm install -g @angular/cli

Angular CLI help in command line:
- ng help

Angular application update instructions at:
- https://update.angular.io/

Creating new application:
- ng new (name of the app without brackets)

Server-side rendering https://v17.angular.io/guide/ssr#why-use-ssr
- creating a new application with SSR: ng new --ssr
- adding SSR to an exisiting project, Angular CLI: ng add @angular/ssr

Prerendering (SSG), Static Site Generation: https://v17.angular.io/guide/prerendering
- prerendering a static page adding SSR capabilities, Angular CLI: ng add @angular/ssr
- generating static pages running build command: ng build

Compiling and running the application (Angular CLI from project folder):
- ng serve

Accessing app from browser:
- http://localhost:4200