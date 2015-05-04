# @getable/lato [![NPM version][npm-image]][npm-url]

CSS component for the lato font

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [Install](#install)
- [Usage](#usage)
- [Developing](#developing)
  - [Requirements](#requirements)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Install

```sh
npm i -S @getable/lato
```


## Usage

```js
@import "@getable/lato"

body {
  font-family: 'Lato', sans-serif;
}
```

## Developing
To publish, run `npm run release -- [{patch,minor,major}]`

_NOTE: you might need to `sudo ln -s /usr/local/bin/node /usr/bin/node` to ensure node is in your path for the git hooks to work_

### Requirements
* **npm > 2.0.0** So that passing args to a npm script will work. `npm i -g npm`
* **git > 1.8.3** So that `git push --follow-tags` will work. `brew install git`

## License

Artistic 2.0 © [Joey Baker](http://byjoeybaker.com)


[npm-url]: https://npmjs.org/package/@getable/lato
[npm-image]: https://badge.fury.io/js/@getable/lato.svg
[travis-url]: https://travis-ci.org/Getable/@getable/lato
[travis-image]: https://travis-ci.org/Getable/@getable/lato.svg?branch=master
[daviddm-url]: https://david-dm.org/Getable/@getable/lato.svg?theme=shields.io
[daviddm-image]: https://david-dm.org/Getable/@getable/lato
