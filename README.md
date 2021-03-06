# \<test-app\>

[![Build Status](https://travis-ci.org/hiherto-elements/test-app.svg?branch=master)](https://travis-ci.org/hiherto-elements/test-app)


* uses etherscan-api to aaccess etherscan.io
* Polymer 3
* deploys when master successfully builds 
* chrome, firefox, safari supported
* comes with a travis.yml
* [Demo](https://github.com/hiherto-elements/test-app)


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
