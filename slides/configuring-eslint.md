##  Configuring ESLint

There are [many options](http://eslint.org/docs/user-guide/configuring) for configuring runtime environments, global variables, and more.

```js
module.exports = {
    "parserOptions": {
        "ecmaVersion": 6,
        "sourceType": "module" // ES2015 modules
    },
    "env": {
        "es6": true, // Transpiling with Babel
        "browser": true, // Client-side code
        "jquery": true,
        "jasmine": true, // Unit testing
        "node": true, // Integration testing
        "protractor": true,
    },
    "globals": {
        "loadFixtures": true // jasmine-jquery
    }
};
```
