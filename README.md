# benderjs-cli

The command line interface for [Bender.js](https://github.com/benderjs/benderjs). It's used to run locally installed version of Bender.js in the current working directory.

## Compatibility

benderjs-cli is compatible with Bender.js in versions 0.1.x and 0.2.x.

**Warning**: this module is not compatible with global installations of Bender 0.1.x

## Installation

For your convenience, please install benderjs-cli globally.

```
npm install -g benderjs-cli
```

## Usage

For the complete list of commands, please visit [Bender.js repository](https://github.com/benderjs/benderjs#usage).

## Local installation

It is possible to install and use a local copy of benderjs-cli in your project. To do this, first install benderjs-cli without "global" flag:

```
npm install benderjs-cli --save-dev
```

Then, add a new script to your `package.json` file, for example:

```json
...
"scripts": {
  "test": "bender run -b chrome"
}
...
```

Now executing `npm test` command will run the local copy of benderjs-cli using `./node_modules/.bin/bender` executable.

## License

MIT, for license details see: [LICENSE.md](https://github.com/benderjs/benderjs-chai/blob/master/LICENSE.md).
