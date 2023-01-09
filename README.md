# postCss


postcss.config.js


## postcss-preset-env

Without any configuration options, PostCSS Preset Env enables Stage 2 features and supports all browsers.

### stages
The stage option determines which CSS features to polyfill, based upon their stability in the process of becoming implemented web standards.
```js
    plugins: {
        "postcss-preset-env": {
            stage: 2
        }

    }
```

The stage can be 0 (experimental) through 4 (stable), or false. Setting stage to false will disable every polyfill. Doing this would only be useful if you intended to exclusively use the features option.


loader

+ postcss-preset-env https://github.com/csstools/postcss-plugins/tree/main/plugin-packs/postcss-preset-env
+ css-loader https://www.npmjs.com/package/css-loader