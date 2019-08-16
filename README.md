# ESLint config

[![Auxilin.com — Production ready Node, React starter kit for building products at a warp speed](https://raw.githubusercontent.com/auxilincom/component-template/master/assets/cover-black.png)](https://github.com/auxilincom/auxilin)

[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
[![npm version](https://badge.fury.io/js/%40auxilin%2Feslint-config.svg)](https://badge.fury.io/js/%40auxilin%2Feslint-config) 
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](https://github.com/auxilin/eslint-config/blob/master/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![David Dependancy Status](https://david-dm.org/auxilincom/eslint-config.svg)](https://david-dm.org/auxilincom/eslint-config)

[![Watch on GitHub](https://img.shields.io/github/watchers/auxilincom/eslint-config.svg?style=social&label=Watch)](https://github.com/auxilincom/eslint-config/watchers)
[![Star on GitHub](https://img.shields.io/github/stars/auxilincom/eslint-config.svg?style=social&label=Stars)](https://github.com/auxilincom/eslint-config/stargazers)
[![Follow](https://img.shields.io/twitter/follow/auxilin.svg?style=social&label=Follow)](https://twitter.com/auxilin)
[![Tweet](https://img.shields.io/twitter/url/https/github.com/auxilincom/eslint-config.svg?style=social)](https://twitter.com/intent/tweet?text=I%27m%20using%20Auxilin%20components%20to%20build%20my%20next%20product%20🚀.%20Check%20it%20out:%20https://github.com/auxilincom/eslint-config)
[![@auxilin](https://img.shields.io/badge/%F0%9F%92%AC%20Telegram-t.me/auxilin-blue.svg)](https://t.me/auxilin)

ESLint configuration. Currently based on [eslint-config-airbnb](https://github.com/airbnb/javascript).

## Installation

Our default export contains all of our ESLint rules, including ECMAScript 6+ and React. It requires `eslint`, `babel-eslint`, `eslint-plugin-import`, `eslint-plugin-react`, and `eslint-plugin-jsx-a11y`.

Install the correct versions of each package, which are listed by the command:
```bash
npm info "@auxilin/eslint-config@latest" peerDependencies
```

Linux/OSX users can run
```bash
(
  export PKG=@auxilin/eslint-config;
  npm info "$PKG@latest" peerDependencies --json | command sed 's/[\{\},]//g ; s/: /@/g' | xargs npm install --save-dev "$PKG@latest"
)
```

Which produces and runs a command like:
```bash
npm install --save-dev @auxilin/eslint-config eslint@#.#.# babel-eslint@#.#.# eslint-plugin-import@#.#.# eslint-plugin-react@#.#.# eslint-plugin-jsx-a11y@#.#.#
```

Windows users can either install all the peer dependencies manually, or use the [install-peerdeps](https://github.com/nathanhleung/install-peerdeps) cli tool.
```bash
npm install -g install-peerdeps
install-peerdeps --dev @auxilin/eslint-config
```

The cli will produce and run a command like:
```bash
npm install --save-dev @auxilin/eslint-config eslint@#.#.# babel-eslint@#.#.# eslint-plugin-import@#.#.# eslint-plugin-react@#.#.# eslint-plugin-jsx-a11y@#.#.#
```

## Quick example

Add `"extends": "@auxilin/eslint-config"` to your .eslintrc

```javascript
module.exports = {
  "extends": "@auxilin/eslint-config"
}
```

This configuration of the ESLint can be changed. See how to configure ESLint on the [official site](https://eslint.org/docs/user-guide/configuring).

## Change Log

This project adheres to [Semantic Versioning](http://semver.org/).
Every release is documented on the Github [Releases](https://github.com/auxilincom/eslint-config/releases) page.

## License

ESlint-config is released under the [MIT License](https://github.com/auxilincom/eslint-config/blob/master/LICENSE).

## Contributing

Please read [CONTRIBUTING.md](https://github.com/auxilincom/eslint-config/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/ezhivitsa"><img src="https://avatars2.githubusercontent.com/u/6461311?v=4" width="100px;" alt="Evgeny Zhivitsa"/><br /><sub><b>Evgeny Zhivitsa</b></sub></a><br /><a href="https://github.com/auxilincom/eslint-config/commits?author=ezhivitsa" title="Code">💻</a> <a href="https://github.com/auxilincom/eslint-config/commits?author=ezhivitsa" title="Documentation">📖</a> <a href="#ideas-ezhivitsa" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!
