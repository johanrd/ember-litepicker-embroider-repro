## Steps to reproduce
* `yarn install`
* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Experience that your console says:
```
Uncaught (in promise) Error: Could not find module `ranges` imported from `(require)`
    at missingModule (loader.js:247)
    at findModule (loader.js:258)
    at requireModule (loader.js:24)
    at eval (ranges.js:1)
    at Object.../externals/ranges.js (chunk.e2477500aa89d9a25e5b.js:17)
    at __webpack_require__ (chunk.7562d808c5c20b3d6e35.js:31)
    at Function.__webpack_require__.t (chunk.7562d808c5c20b3d6e35.js:96)
    at async Promise.all (:4200/index 0)
```


