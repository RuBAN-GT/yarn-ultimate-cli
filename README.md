# Ultimate Yarn bundle CLI

Forked part of [yarnpkg-cli](https://github.com/yarnpkg/berry/tree/master/packages/yarnpkg-cli) helping to build own Yarn CLI with bult-in plugins.

## Installation

> yarn install

## Build

> yarn build

## How to use

1. Open your project and check that you don't use any yarn plugins and custom versions.
2. Execute the next command:

```sh
curl -L 'https://raw.githubusercontent.com/RuBAN-GT/yarn-ultimate-cli/master/bundles/yarn.js' > '/tmp/yarn.js'
yarn set version berry && yarn set version /tmp/yarn.js
```

## Bult-in plugins

### Custom plugins:

- [yarn-plugin-enhanced-workspace](https://github.com/RuBAN-GT/yarn-plugin-enhanced-workspaces)

### Default yarn plugins:

- @yarnpkg/plugin-essentials
- @yarnpkg/plugin-compat
- @yarnpkg/plugin-dlx
- @yarnpkg/plugin-file
- @yarnpkg/plugin-git
- @yarnpkg/plugin-github
- @yarnpkg/plugin-http
- @yarnpkg/plugin-init
- @yarnpkg/plugin-link
- @yarnpkg/plugin-nm
- @yarnpkg/plugin-npm
- @yarnpkg/plugin-npm-cli
- @yarnpkg/plugin-pack
- @yarnpkg/plugin-patch
- @yarnpkg/plugin-pnp
- @yarnpkg/plugin-pnpm
- @yarnpkg/plugin-version
- @yarnpkg/plugin-workspace-tools
- @yarnpkg/plugin-interactive-tools
