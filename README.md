# crud-vue-app

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## Router

  authentication flow is redirecting the user back to your app with the token values in the URL. The Auth.handleCallback() component included in the SDK handles the redirect and persists the tokens on the browser.

  The SDK comes with the method auth.authRedirectGuard() that checks matched routes’ metadata for the key requiresAuth and redirects the user to the authentication flow if they are not authenticated.

## Server

  SQLite to limit external dependencies

  Each post has a title and body. (The fields createdAt, and updatedAt are added by Sequelize automatically). With Sequelize, you define models by calling define() on your instance.

  Epilogue creates flexible REST endpoints from Sequelize models within an Express app. If you ever coded REST endpoints you know how much repetition there is. D.R.Y

Verify Your JWT
  This is the most crucial component of your REST API server. Without this middleware any user can perform CRUD operations on our database. If no authorization header is present, or the access token is invalid, the API call will fail and return an error.

## API

  centralize my API integrations into a single helper module. This keeps the code in components much cleaner and provides single location in case you need to change anything with the API request.
