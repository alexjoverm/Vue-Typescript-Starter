# Vue TypeScript Starter

Basic starter based on [Webpack](https://github.com/vuejs-templates/webpack) from [Vue cli](https://github.com/vuejs/vue-cli) used in the course **[Use TypeScript to Develop Vue.js Web Applications](https://egghead.io/courses/use-typescript-to-develop-vue-js-web-applications)**

## How to TypeScriptify your Vue project

Here are the steps taken in this starter:

 - Add [tsconfig.json](https://github.com/alexjoverm/Vue-Typescript-Starter/blob/master/tsconfig.json)
 - Add [tsloader to build/webpack.base.conf.js](https://github.com/alexjoverm/Vue-Typescript-Starter/blob/master/build/webpack.base.conf.js#L30), plus add/update extensions to ts. Remember to install ts-loader and TypeScript
 - Add [vue-shim.d.ts](https://github.com/alexjoverm/Vue-Typescript-Starter/blob/master/vue-shim.d.ts) in order to TypeScript recognize and treat .vue files
 - [build/vue-loader.conf.js](https://github.com/alexjoverm/Vue-Typescript-Starter/blob/master/build/vue-loader.conf.js#L12): add `esModule: true`
 - Rename `.js` to `.ts` files in `src` folder
 - Use `lang="ts"` in .vue files
