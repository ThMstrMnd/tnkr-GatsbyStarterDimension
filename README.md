# THIS TEMPATE DOESN'T WORK.
## Did all what was said in the error message. 
Error: 

✖ ｢wdm｣: 
ERROR in ./src/assets/scss/main.scss (./node_modules/css-loader??ref--13-oneOf-1-1!./node_modules/postcss-loader/lib??postcss-3!./node_modules/sass-loader/lib/loader.js??ref--13-oneOf-1-3!./src/assets/scss/main.scss)
Module build failed (from ./node_modules/sass-loader/lib/loader.js):
Error: Missing binding /home/me/The_Inceptors/gatsby-starter-dimension/node_modules/node-sass/vendor/linux-x64-67/binding.node
Node Sass could not find a binding for your current environment: Linux 64-bit with Node.js 11.x

Found bindings for the following environments:
  - Linux 64-bit with Node.js 10.x

This usually happens because your environment has changed since running `npm install`.
Run `npm rebuild node-sass` to download the binding for your current environment.
    at module.exports (/home/me/The_Inceptors/gatsby-starter-dimension/node_modules/node-sass/lib/binding.js:15:13)
    at Object.<anonymous> (/home/me/The_Inceptors/gatsby-starter-dimension/node_modules/node-sass/lib/index.js:14:35)
    at Module._compile (/home/me/The_Inceptors/gatsby-starter-dimension/node_modules/v8-compile-cache/v8-compile-cache.js:178:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:749:10)
    at Module.load (internal/modules/cjs/loader.js:630:32)
    at tryModuleLoad (internal/modules/cjs/loader.js:570:12)
    at Function.Module._load (internal/modules/cjs/loader.js:562:3)
    at Module.require (internal/modules/cjs/loader.js:667:17)
    at require (/home/me/The_Inceptors/gatsby-starter-dimension/node_modules/v8-compile-cache/v8-compile-cache.js:159:20)
    at Object.sassLoader (/home/me/The_Inceptors/gatsby-starter-dimension/node_modules/sass-loader/lib/loader.js:46:72)
 @ ./src/assets/scss/main.scss 2:14-227 21:1-42:3 22:19-232
 @ ./src/components/layout.js
 @ ./src/pages/page-2.js
 @ ./.cache/sync-requires.js
 @ ./.cache/app.js
 @ multi event-source-polyfill (webpack)-hot-middleware/client.js?path=/__webpack_hmr&reload=true&overlay=false ./.cache/app
ℹ ｢wdm｣: Failed to compile.

# gatsby-starter-dimension

**This is a starter for Gatsby.js V2.**

**The older V1 version of this starter can be found on the v1 branch:**

Gatsby.js V2 starter based on the Dimension site template, designed by HTML5 UP. Check out https://codebushi.com/gatsby-starters/ for more Gatsby starters and templates.

## Preview

https://gatsby-dimension.surge.sh/

## Installation

Install this starter (assuming Gatsby is installed) by running from your CLI:
<br/>
`gatsby new gatsby-starter-dimension https://github.com/codebushi/gatsby-starter-dimension`

Run `gatsby develop` in the terminal to start the dev site.
