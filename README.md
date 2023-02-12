# @schuijers/prettier-config [![GitHub Build Status][shield-github-build-status]][shield-github-build-status] [![npm][shield-npm]][npm] [![MIT License][shield-license]][license]

My shareable Prettier config.

## Installation

```shell script
# npm
npm install --save-dev @schuijers/prettier-config

# yarn
yarn add --dev @schuijers/prettier-config

# pnpm
pnpm add --save-dev @schuijers/prettier-config
```

This library has a required `peerDependencies` listing for [`prettier`](https://prettier.io/).

## Usage

Reference `@schuijers/prettier-config` in your `package.json`.

<!-- prettier-ignore -->
```json
{
  "name": "my-cool-library",
  "version": "1.42.0",
  "prettier": "@schuijers/prettier-config"
}
```

Or, you can use it in other ways as described in the
[official documentation](https://prettier.io/docs/en/configuration.html#sharing-configurations).

## License

[MIT][license] &copy; [Martijn Schuijers][me]

[license]: ./LICENSE
[me]: https://github.com/schuijers
[npm]: https://npmjs.org/package/@schuijers/prettier-config
[shield-github-build-status]:
  https://github.com/schuijers/prettier-config/workflows/Release/badge.svg
[shield-license]: https://img.shields.io/badge/License-MIT-lavender.svg
[shield-npm]: https://img.shields.io/npm/v/@schuijers/prettier-config.svg
