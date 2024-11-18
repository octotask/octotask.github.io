---
title: size-plugin
description: A GitHub 🤖 that helps you to keep an 👁️ on static assert 📦 sizes
  of your application and gives instant feedback 📝 for developer whenever they
  make a change
slug: size-plugin
screenshots:
  - https://github.com/kuldeepkeshwar/size-plugin-bot/raw/master/static/images/sample.png?raw=true
authors:
  - kuldeepkeshwar
repository: kuldeepkeshwar/size-plugin-bot
host: https://size-plugin-bot.glitch.me
stars: 84
updated: 2024-06-18 02:13:22 UTC
organizations:
  - antvis
  - tannerlinsley
  - DestinyItemManager
  - ignatandrei
  - admdev8
  - preactjs
  - CartoonFan
  - tilde-lab
  - Ignitus
  - evryfs
---


[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](https://github.com/kuldeepkeshwar/size-plugin-bot/#contributors-)

<p align="center">
  <img src="https://github.com/kuldeepkeshwar/size-plugin-bot/blob/master/static/images/icon.png?raw=true" alt="size-plugin" >
</p>
<p align="center">
  <h1 align="center">size-plugin</h1>
</p>

> A GitHub 🤖 built with Probot that helps you to keep an 👁️ on static assert 📦 sizes of your application and gives instant feedback 📝 for developer whenever they make change.

##### 🤖 comments the gzipped sizes of your webpack assets and the changes since the last build into the relevant PR

## Usage

First add an instance of the [size-plugin](https://github.com/GoogleChromeLabs/size-plugin) to your webpack configuration:

```diff
// webpack.config.js
+ const SizePlugin = require('size-plugin');

module.exports = {
  plugins: [
+    new SizePlugin({publish:true})
  ]
}
```

Second Simply [install the app](https://github.com/apps/size-plugin) and make some changes, open a pr and watch the magic happen 😊

<p align="center">
  <img src="https://github.com/kuldeepkeshwar/size-plugin-bot/blob/master/static/images/sample.png?raw=true" alt="size-plugin commenting on a PR with bundle stats" width="760">
</p>

Currently works with [Travis CI](https://travis-ci.org), [CircleCI](https://circleci.com/), [Wercker](http://www.wercker.com), and [Drone](http://readme.drone.io/).

Using a different CI? Under the hood, [size-plugin](https://github.com/GoogleChromeLabs/size-plugin) uses [ci-env](https://github.com/siddharthkp/ci-env) to extract meta information which works perfectly with Custom CI 🙃

## Configure Bot

Create a file `.github/size-plugin.yml`.

example 👇

```yml
size-files: # list of size*.json files incase you have multiple packages.
    - size-plugin-browser.json
    - size-plugin-ssr.json
base-branches: # base branches against which bot can open a pull request.
    - master
    - next
```

## Contributing

If you have suggestions for how size-plugin could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](https://github.com/kuldeepkeshwar/size-plugin-bot/blob/master/CONTRIBUTING.md).
