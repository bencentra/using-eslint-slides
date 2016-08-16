##  Setting Up ESLint

Install\* `eslint` in your project:

```bash
npm install --save-dev eslint
```

Add an [npm script](https://css-tricks.com/why-npm-scripts/) in `package.json`:

```json
"scripts": {
    "lint": "eslint src/ spec/"
}
```

Run it:

```bash
npm run lint
```

<p class="small"><em>\*ESLint 3.x requires Node >= 4.x to run!<br>If you're stuck on Node < 4.x, install eslint@2.x</em></p>
