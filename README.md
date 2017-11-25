# Angular 5 HTTP Client Demo App

This is a demo application showing how to use the HttpClient service and Observables in Angular 5.

For background on the topic of Angular HTTP requests, please see my blog posts:

https://www.metaltoad.com/blog/angular-2-http-observables-and-concurrent-data-loading

https://www.metaltoad.com/blog/angular-2-using-http-service-write-data-api

Note: This app uses the new and improved HttpClient service introduced in Angular 4.3. If you are using Angular 2 or Angular 4 v4.2 and below, see [this older demo using the deprecated Http service](https://github.com/kdechant/angular2-http-demo).

# What's in here

- app.js - a simple Express app which acts as the back-end API.
- src/app/ - this folder contains the Angular app
- config/ - this folder contains webpack-related scripts

# Running the app

To run this application, you need NodeJS and NPM installed on your system. Then, run the following commands from your command prompt:

```
npm install
npm start
```

This will transpile the TypeScript files, bundle everything using Webpack, and start the Node server. The app will be available at [http://localhost:3000/](http://localhost:3000/)
