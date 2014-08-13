![tire-logo](http://static.forsmo.me/tire/logo/tire.js-100x100.png)

Tire [![Build Status](https://travis-ci.org/tirejs/tire.png?branch=master)](https://travis-ci.org/tirejs/tire)
========

**This project is not maintained anymore**

Tire is a lightweight JavaScript library for modern browsers. The goal is to create a framework that's around 15-16kb minified and 5-6kb minified and gzipped. The syntax is inspired from jQuery. It is modular so you can extend it however you like, also replace our features with your own. 

Fixes for older browsers increase the file size and we don't want that. So if you like a library to support Internet Explorer 6 or 7, Tire isn't for you. 

That said, all features can probably be rewritten/extended to add support for old browsers. In that case, you have to create a fork of Tire and fix it yourself.

## Browser support 

* Chrome
* Safari 4.0.5
* Internet Explorer 8
* Firefox 3.5
* Opera 10

#### Older browsers

Tire may work in older browsers but is not tested in older than the above.

## Documentation

* Read the [docs](http://tirejs.github.io).

## Download

Current release: 1.3.1

* [tire.js](http://cdn.jsdelivr.net/tire/1.3.1/tire.js) - _49kB uncompressed (lots of comments), for development_
* [tire.min.js](http://cdn.jsdelivr.net/tire/1.3.1/tire.min.js) - _3.9kB when gzipped, for production_

Please do not hotlink directly to the files hosted on [code.tirejs.com](http://code.tirejs.com). Download a local copy instead.

### CDN

* [tire.js](http://cdn.jsdelivr.net/tire/1.3.1/tire.js) `//cdn.jsdelivr.net/tire/1.3.1/tire.js`
* [tire.min.js](http://cdn.jsdelivr.net/tire/1.3.1/tire.min.js) `//cdn.jsdelivr.net/tire/1.3.1/tire.min.js`

## Build

```sh
npm install
make
```

On Windows
  
```sh
npm install
grunt.cmd
```

## Test

Install `connect` via `npm` and start the server. This will create a local server (on port 3000) so the ajax tests don't failes. Be sure to build tire first or all tests will fail! Then you can open `http://localhost:3000/` in your browser to run the tests.

```sh
npm install
node server.js
```
  
## Contribute

Everyone is welcome to contribute with patches, bug-fixes and new features.

1. Create an [issue](https://github.com/tirejs/tire/issues) on Github so the community can comment on your idea.
2. Fork `tire` on Github.
3. Create a new branch: `git checkout -b my_branch`.
4. Create tests for the changes you made.
5. Make sure you pass both existing and newly inserted tests.
6. Commit your changes.
7. Push to your branch: `git push origin my_branch`.
8. Create a pull request against `*-wip` branches.

**Note:**

* Please follow the code style in Tire.
* If you are making several changes at once please divide them into multiple pull requests.
* Always create the pull request against the `*-wip` branches (use `master` when no `*-wip` exists), not the `master`.
