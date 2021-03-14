# International Telephone Input for Angular (NgxIntlTelInput)

[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)

An Angular package for entering and validating international telephone numbers. It adds a flag dropdown to any input, detects the user's country, displays a relevant placeholder and provides formatting/validation methods.
## `NOTE`: 
This a forked version of [Origin Implementation](https://www.npmjs.com/package/ngx-intl-tel-input) and below bugs resolved:
  - Focus to input on open countries menu
## Installation

### Install Dependencies

`$ npm install intl-tel-input@17.0.3 --save`

`$ npm install google-libphonenumber --save`

`$ ng add ngx-bootstrap`

If you do not wish to use Bootstrap's global CSS, we now package the project with only the relevant
bootstrap styling needed for the dropdown. As such, you can remove the bootstrap styling from `angular.json`.

Further, Angular CLI should tree-shake the rest of Ngx-Boostrap away if you don't utilize other dependencies from
the bootstrap package. This should keep this dependency a lean feature-add

### Add Dependency Style

Add _'intl-tel-input'_ style file:

`./node_modules/intl-tel-input/build/css/intlTelInput.css`

to **angular.json** styles array:

```json

"styles": [
  "./node_modules/intl-tel-input/build/css/intlTelInput.css",
  "src/styles.css"
],

```

### Install This Library

`$ npm install ngx-intl-tel-input --save`

## Usage

### Import

Add `NgxIntlTelInputModule` to your module file:

```javascript
imports: [NgxIntlTelInputModule];
```

