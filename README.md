# Virtual DOM diff/patch benchmark

Comparing performance of the diff/patch operations in various virtual
dom libraries.

- [VDom](https://github.com/localvoid/vdom) (Dart)
- [React](http://facebook.github.io/react/) (JavaScript)
- [Mithril](http://lhorie.github.io/mithril/index.html) (JavaScript)
- [VirtualDom](https://github.com/Matt-Esch/virtual-dom) (JavaScript)

## [Run benchmark](http://localvoid.github.io/vdom-benchmark/)

## Build instructions

```sh
$ npm install
$ NODE_ENV=production gulp
$ pub build --mode=release
```