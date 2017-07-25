[![Build Status](https://img.shields.io/travis/MaritzSTL/mtz-lazy-imports-handler-behavior/master.svg?style=flat-square)](https://travis-ci.org/MaritzSTL/mtz-lazy-imports-handler-behavior)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/MaritzSTL/mtz-lazy-imports-handler-behavior)

# \<mtz-lazy-imports-handler-behavior\>

Pulls in the `Polymer.LazyImportsBehavior` and listens for an event to tell an instance of this behavior to attempt to import a lazy-group within the provided domain, if it is found then it will stop the event propagation. Listens for events on the use-capture event cycle.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
