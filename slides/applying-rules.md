##  Applying [Rules](http://eslint.org/docs/rules/)

Create an `.eslintrc.js` file with a "rules" section:

```js
module.exports = {
    "rules": {
        "no-param-reassign": "warning",
        "curly": ["error", "all"],
        "comma-dangle": "off"
    }
};
```

Rules can be set to the following values:

* `"off"` or `0` - Turn off the rule
* `"warn"` or `1` - Violated rule is a warning (exit 0)
* `"error"` or `2` - Violated rule is an error (exit 1)
