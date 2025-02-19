# &lt;vaadin-confirm-dialog&gt;

> ⚠️ Starting from Vaadin 20, the source code and issues for this component are migrated to the [`vaadin/web-components`](https://github.com/vaadin/web-components/tree/master/packages/vaadin-confirm-dialog) monorepository.
> This repository contains the source code and releases of `<vaadin-confirm-dialog>` for the Vaadin versions 10 to 19.

[&lt;vaadin-confirm-dialog&gt;](https://vaadin.com/components/vaadin-confirm-dialog) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

[Live Demo ↗](https://vaadin.com/components/vaadin-confirm-dialog/html-examples)
|
[API documentation ↗](https://vaadin.com/components/vaadin-confirm-dialog/html-api)

[![npm version](https://badgen.net/npm/v/@vaadin/vaadin-confirm-dialog)](https://www.npmjs.com/package/@vaadin/vaadin-confirm-dialog)
[![Published on Vaadin Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/vaadinvaadin-confirm-dialog)
[![Discord](https://img.shields.io/discord/732335336448852018?label=discord)](https://discord.gg/PHmkCKC)

```html
<vaadin-confirm-dialog header="Unsaved changes" confirm-text="Save" on-confirm="save"
  cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
  Do you want to save or discard your changes before navigating away?
</vaadin-confirm-dialog>
```

[<img src="https://raw.githubusercontent.com/vaadin/vaadin-confirm-dialog/master/screenshot.png" width="200" alt="Screenshot of vaadin-confirm-dialog">](https://vaadin.com/components/vaadin-confirm-dialog)


## Installation

The Vaadin components are distributed as Bower and npm packages.
Please note that the version range is the same, as the API has not changed.
You should not mix Bower and npm versions in the same application, though.

Unlike the official Polymer Elements, the converted Polymer 3 compatible Vaadin components
are only published on npm, not pushed to GitHub repositories.

### Polymer 2 and HTML Imports compatible version

Install `vaadin-confirm-dialog`:

```sh
bower i vaadin/vaadin-confirm-dialog --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/vaadin-confirm-dialog/vaadin-confirm-dialog.html">
```
### Polymer 3 and ES Modules compatible version


Install `vaadin-confirm-dialog`:

```sh
npm i @vaadin/vaadin-confirm-dialog --save
```

Once installed, import it in your application:

```js
import '@vaadin/vaadin-confirm-dialog/vaadin-confirm-dialog.js';
```

## Getting Started

Vaadin components use the Lumo theme by default.

## The file structure for Vaadin components

- `src/vaadin-confirm-dialog.html`

  Unstyled component.

- `theme/lumo/vaadin-confirm-dialog.html`

  Component with Lumo theme.

- `vaadin-confirm-dialog.html`

  Alias for theme/lumo/vaadin-confirm-dialog.html


## Running demos and tests in browser

1. Fork the `vaadin-confirm-dialog` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `vaadin-confirm-dialog` directory, run `npm install` and then `bower install` to install dependencies.

1. Make sure you have [polymer-cli](https://www.npmjs.com/package/polymer-cli) installed globally: `npm i -g polymer-cli`.

1. Run `polymer serve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/vaadin-confirm-dialog/demo
  - http://127.0.0.1:8080/components/vaadin-confirm-dialog/test


## Running tests from the command line

> [!WARNING]
> Running tests locally from the CLI does not work due to outdated dependencies. Run tests via SauceLabs or in the browser instead.

1. When in the `vaadin-confirm-dialog` directory, run `polymer test`


### Big Thanks

Cross-browser Testing Platform and Open Source <3 Provided by [Sauce Labs](https://saucelabs.com).


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `npm run lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Contributing

  To contribute to the component, please read [the guideline](https://github.com/vaadin/vaadin-core/blob/master/CONTRIBUTING.md) first.


## License

Commercial Vaadin Add-on License version 3 (CVALv3). For license terms, see LICENSE.

Vaadin collects development time usage statistics to improve this product. For details and to opt-out, see https://github.com/vaadin/vaadin-usage-statistics.
