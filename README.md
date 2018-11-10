# es6router
Vanilla Javascript router targeting ES6/ECMAScript 2015 and later.

es6router is based on Navigo with the following differences:

* It's an es6 module so you can import it with `import Router from '/router.js';`
* All hash-based support is removed since any browser supporting es6 also supports pushState
* The root is protocol+host by default
* The router attribute is `app-route` instead of `data-navigo`
