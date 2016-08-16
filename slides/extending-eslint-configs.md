##  Extending ESLint Configs

For example, you can use [Airbnb's JS Style Guide](https://github.com/airbnb/javascript):

```bash
npm install --save-dev eslint-config-airbnb-base
```

And extend in your config, overriding existing rules:

```js
module.exports = {
    "extends": "airbnb-base",
    "rules": {
        "comma-dangle": 0
    }
};
```
