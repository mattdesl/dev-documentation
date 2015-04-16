# dev-documentation

A documentation-building server. Heavily inspired and partially copied from mattdesl's
[excellent budo project](https://github.com/mattdesl/budo).

This will

* run a server for you
* automatically open http://localhost:8000/
* automatically rebuild documentation when your code changes
* automatically reload the page for you if you have [LiveReload](http://livereload.com/) installed.

## Installation

This packages the documentationjs project, so it is installable with
one command.

```sh
$ npm install dev-documentation
```

## Usage

For a single file

```sh
$ dev-documentation index.js
```

Or just run it in a project directory

```sh
$ cd my-project/
$ dev-documentation
```
