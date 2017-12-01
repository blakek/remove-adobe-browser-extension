# remove-adobe-browser-extension

[![Greenkeeper badge](https://badges.greenkeeper.io/blakek/remove-adobe-browser-extension.svg)](https://greenkeeper.io/)

> Removes Adobe Acrobat's browser plugin (currently macOS only; supports Firefox
> and Safari)

I'm not sure why Adobe thinks it's okay to keep installing browser plugins
without asking. This removes those unwanted files.

## Usage

Remove extensions for all known browsers:

```bash
remove-adobe-browser-extension
```

Remove extensions for a particular browser

```bash
remove-adobe-browser-extension firefox
```

**Known browsers:**

* `firefox`
* `safari`

**Options:**

* `-h, --help` - show this help text
* `-v, --verbose` - be more verbose
* `-V, --version` - print script version and exit

## Install

### Option 1: use `yarn` or `npm`

If using [npm](https://www.npmjs.com/):

```shell
npm i -g remove-adobe-browser-extension
```

If using [Yarn](https://yarnpkg.com/):

```shell
yarn global add remove-adobe-browser-extension
```

### Option 2: manual installation

1. Either
   [clone this repository](https://help.github.com/articles/cloning-a-repository/)
   or
   [download the ZIP file](https://github.com/blakek/remove-adobe-browser-extension/archive/master.zip)
2. Add this to your $PATH

## License

[MIT](https://raw.githubusercontent.com/blakek/remove-adobe-browser-extension/master/LICENSE)
