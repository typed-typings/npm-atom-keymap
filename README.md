# Typed Atom Keymap  [![Build Status](https://travis-ci.org/typed-typings/npm-atom-keymap.svg?branch=master)](https://travis-ci.org/typed-typings/npm-atom-keymap)

[![Greenkeeper badge](https://badges.greenkeeper.io/types/npm-atom-keymap.svg)](https://greenkeeper.io/)


The type definition for [`atom-keymap`](https://github.com/atom/atom-keymap.git)

## LICENSE

MIT

## Contributing

```sh
# Fork this repo
npm install

npm run watch

# add tests, make changes, pass tests ... then [ctrl+c]
npm run publish
```

## Updating

Update `typings.json/version` to match the source version you are typing against.
e.g. if you are creating typings for `chai@3.5.0`, then:

```js
// typings.json
{
  "version": "3.5.0"
  // ...
}
```

## Note

Currently the test is not running.
Having the same issue as described [here](https://github.com/atom/atom-keymap/issues/134)
