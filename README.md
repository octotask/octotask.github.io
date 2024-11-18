# octotask.github.io

This is the home of octotask.github.io, a website for [octotask](https://github.com/octotask/octotask) documentation, apps, how-to guides and more.

## Documentation

The majority of documentation on the site is drawn from [the octotask docs](https://github.com/octotask/octotask/blob/master/docs/). If you have requests for documentation additions to octotask, please open an issue in [octotask/octotask](https://github.com/octotask/octotask), or if you want to add them yourself, feel free to open a pull request there.

## App Showcase

We also use this website to show off some of the cool octotask apps built by the community. If you would like to have your app listed there, check out our [Contributing Guidelines](https://github.com/octotask/octotask.github.io/blob/master/CONTRIBUTING.md) for more information about what the requirements are to do that.

## Install and Usage

If you'd like to work on this repository, clone it. We use [11ty](https://www.11ty.dev/) to build the website, hosted on [GitHub Pages](https://pages.github.com/). We also use Git submodules to pull docs from the docs folder in [octotask/octotask](https://github.com/octotask/octotask/tree/master/docs).

Once you've cloned this repo, run these commands in this directory:

```bash
# Only needed the first time:
$ yarn
# To build dist/styles.css in assets/ if dist doesn't exist
$ yarn sass
# And each time you work locally:
$ yarn watch
```

You should then be able to navigate to the server address, and see live edits you make render in your browser. You'll likely have to familiarize yourself with how 11ty works to do larger edits, but it's worth the effort!

## Contribute

We'd love to have you contribute! PRs are gladly accepted, and issues are also great. If you're thinking about a major PR, it would be better to open an issue first to talk about it.

If you're interested in contributing, check out our [contributing docs](CONTRIBUTING.md) to get started.

Want to get more involved with the Octotask community? [Take a look at our community page](https://octotask.github.io/community/)!

## License

This website is licensed [CC-BY-4.0](LICENSE). The Octotask logo is licensed [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.en). It was found on [wikimedia.org](https://commons.wikimedia.org/wiki/File:Robot-clip-art-book-covers-feJCV3-clipart.png) and is from clipartkid.com.
