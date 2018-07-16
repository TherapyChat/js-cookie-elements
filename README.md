[![Build status](https://travis-ci.org/TherapyChat/js-cookie-elements.svg?branch=master)](https://travis-ci.org/TherapyChat/js-cookie-elements)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/therapychat/js-cookie-elements)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com)

# \<js-cookie-elements\>

Web Component to use [js-cookie](https://github.com/js-cookie/js-cookie)

Example of use:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../paper-input/paper-input.html">
    <link rel="import" href="../paper-button/paper-button.html">
    <link rel="import" href="js-cookie-elements.html">

    <next-code-block></next-code-block>

    <p>The current value for <code>jsCookie</code> is: <code>[[value]]</code>. Check your browser cookies!</p>

  </template>
</custom-element-demo>
```
-->
```html
<js-cookie-element
  name="jsCookie"
  value="it works"
  current-value="{{value}}"
></js-cookie-element>
```

## Changelog

See [CHANGELOG](./CHANGELOG.md) file.

## Contributing

Please read [CONTRIBUTING](./CONTRIBUTING.md) file to follow good practices.

You will need [NodeJS](https://nodejs.org).

1. Close the repo: `git clone git@github.com:TherapyChat/js-cookie-elements.git`
1. Install dependencies: `npm install`
1. Code!
1. Test: `npm test`
1. Create a [Pull Request](https://github.com/therapychat/js-cookie-elements/pulls)

### Contributors

- [Alberto Fernandez](https://github.com/AlbertoFdzM)

## License

This project is available under the `Apache License 2.0`. See the [LICENSE](./LICENSE) file for more info.
