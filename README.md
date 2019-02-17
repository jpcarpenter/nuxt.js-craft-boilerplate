# Nuxt.js Craft Boilerplate

> Basic front-end and back-end boilerplate for Nuxt.js together with Craft 3.

## Nuxt.js
Can be found in the `frontend` directory.

### Build Setup
```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project (may not work)
$ npm run generate

# generate IDE Tailwind file
$ npm run tailwind
```

### Modules
This installation comes pre-installed with the following Nuxt.js modules:
* [@nuxtjs/apollo](https://github.com/nuxt-community/apollo-module): Nuxt.js module to use Vue-Apollo to integrate GraphQL.
* [@nuxtjs/axios](https://github.com/nuxt-community/axios-module): Secure and easy axios integration with Nuxt.js.
* [@nuxtjs/dotenv](https://github.com/nuxt-community/dotenv-module): Loads your .env file into your application context.
* [@nuxtjs/proxy](https://github.com/nuxt-community/proxy-module): The one-liner node.js http-proxy middleware solution for Nuxt.js using http-proxy-middleware.
* [@nuxtjs/redirect-module](https://github.com/nuxt-community/redirect-module): Carrying over Craft redirects configuration.

## Craft 3
Can be found in the `backend` directory.

### Installation
Requires your own PHP server.
```bash
# install dependencies
$ composer install
```

### Plugins
Comes pre-installed with [CraftQL](https://github.com/markhuot/craftql), [SEOmatic](https://github.com/nystudio107/craft-seomatic), [Redactor](https://github.com/craftcms/redactor) and [Redirect](https://github.com/Dolphiq/craft3-plugin-redirect).

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).
