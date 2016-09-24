[npm-image]: https://badge.fury.io/js/generator-jsmodules.svg
[npm-url]: https://npmjs.org/package/generator-jsmodules
[travis-image]: https://travis-ci.org/sotayamashita/generator-jsmodules.svg?branch=master
[travis-url]: https://travis-ci.org/sotayamashita/generator-jsmodules
[daviddm-image]: https://david-dm.org/sotayamashita/generator-jsmodules.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/sotayamashita/generator-jsmodules
[yo]: https://github.com/yeoman/yo
[me]: https://github.com/sotayamashita

# generator-jsmodules [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]

> Scaffold out a node module

## Install

First, install [Yeoman](http://yeoman.io) and generator-jsmodules using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)):

```bash
npm install -g yo generator-jsmodules
```

## Usage

Generate your new project with [yo][yo]:

```bash
yo jsmodules
```

There are multiple command-line options available:

```bash
$ yo jsmodules --help

  Usage:
    yo jsmodules [options]

  Options:
    --help          # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers                      Default: false
    --skip-install  # Do not automatically install dependencies           Default: false
    --cli           # Add a CLI
    --coverage      # Add code coverage with nyc
    --coveralls     # Upload coverage to coveralls.io (implies --coverage)
```

## License

MIT © [Sota Yamashita][me]
