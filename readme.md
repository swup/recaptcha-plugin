# Swup Recaptcha Plugin

This is a plugin for [swup](https://swup.js.org/) - complete, flexible, extensible and easy to use page transition library for your web.

## Instalation

This plugin can be installed with npm

```bash
npm install swup-recaptcha-plugin
```

and included with import

```javascript
import SwupRecaptchaPlugin from 'swup-recaptcha-plugin';
```

or included from the dist folder

```html
<script src="./dist/SwupRecaptchaPlugin.js"></script>
```

## Usage

To run this plugin, include an instance in the swup options.

```javascript
const swup = new Swup({
  plugins: [new SwupRecaptchaPlugin()]
});
```
