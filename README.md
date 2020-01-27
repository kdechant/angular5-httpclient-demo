## Note: This project is archived.

This is built on an old version of Angular that is no longer supported. **This project is for information only and will not receive any further support or upgrades**.

---

# Angular 5 HTTP Client Demo App

This is a demo application showing how to use the HttpClient service and Observables in Angular 5.

For background on the topic of Angular HTTP requests, please see my blog post:

https://www.metaltoad.com/blog/angular-5-making-api-calls-httpclient-service

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

# Hacking and making local changes

This project does not support browser-sync or the live reloading that comes standard with the Angular CLI. If you want to edit the files and see your changes, you'll need to stop the `npm start` process and start it again in order for your changes to appear.

Sorry for the inconvenience, but this is an old project using an outdated version of Angular. I'm not going to spend the time improving the build pipeline.
