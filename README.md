# nuxt-fontawesome
Nuxt Fontawesome 6 configuration with help of https://github.com/nuxt-community/fontawesome-module

# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# For yarn
$ yarn add @nuxtjs/fontawesome @fortawesome/free-solid-svg-icons @fortawesome/free-regular-svg-icons @fortawesome/free-brands-svg-icons -D

# For npm
npm install @nuxtjs/fontawesome @fortawesome/free-solid-svg-icons @fortawesome/free-regular-svg-icons @fortawesome/free-brands-svg-icons -D

# Must run 
$ yarn add @fortawesome/vue-fontawesome@latest
or
$ npm install --save @fortawesome/vue-fontawesome@latest

# then run otherwise it will install old core version of Fontawesome
yarn add @fortawesome/fontawesome-svg-core
or
npm install --save @fortawesome/fontawesome-svg-core

# nuxt-config.js
  buildModules: [
    '@nuxtjs/fontawesome',
  ],
  fontawesome: {
    icons: {
      solid: true,
      regular:true,
      brands:true
    }
  },
  
 ## Enjoy 
