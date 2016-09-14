# Common JSX coding style - ESLint Shareable Config

__An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for JSX support in [JavaScript Common coding Style](https://github.com/Nicolab/eslint-config-common)__

This module is for advanced users. You probably want to use [`common`](https://github.com/Nicolab/eslint-config-common) instead :)


## Install

```sh
npm install eslint-config-common-jsx
```


## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

This Shareable Config adds extra JSX style rules to the baseline JavaScript Common Style
rules provided in
[`eslint-config-common`](https://www.npmjs.com/package/eslint-config-common).
It doesn't assume that you're using React, so other virtual DOM libraries like
`virtual-dom` and `deku` are supported.

Even thought this config is JSX only (no React), it makes use of
[`eslint-plugin-react`](https://npmjs.com/package/eslint-plugin-react) for its generic
JSX rules.

(If you want React-specific rules too, consider using
[`eslint-config-common-react`](https://www.npmjs.com/package/eslint-config-common-react)
instead.)

Here's how to install everything you need:

```sh
npm install eslint-config-common eslint-config-common-jsx eslint-plugin-promise eslint-plugin-react eslint-plugin-standard
```

Then, add this to your .eslintrc file:

```
{
  "extends": ["common", "common-jsx"]
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.


## Learn more

The rules of the Common coding style are based and/or inspired by:

 * [Google's JavaScript Style Guide](https://google.github.io/styleguide/javascriptguide.xml)
 * [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
 * [Felix's Node.js Style Guide](https://github.com/felixge/node-style-guide)
 * [Feross's JavaScript Standard Style](http://standardjs.com)


## LICENSE

[MIT](https://github.com/Nicolab/eslint-config-common-jsx/blob/master/LICENSE) (c) 2016, Nicolas Tallefourtane.


## Author

| [![Nicolas Tallefourtane - Nicolab.net](http://www.gravatar.com/avatar/d7dd0f4769f3aa48a3ecb308f0b457fc?s=64)](http://nicolab.net) |
|---|
| [Nicolas Talle](http://nicolab.net) |
| [![Make a donation via Paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=PGRH4ZXP36GUC) |