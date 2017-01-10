# GH Jenkins [![Build Status](https://secure.travis-ci.org/node-gh/gh-jenkins.svg?branch=master)](https://travis-ci.org/node-gh/gh-jenkins) [![NPM version](https://badge.fury.io/js/gh-jenkins.svg)](http://badge.fury.io/js/gh-jenkins) [![Dependency Status](https://david-dm.org/node-gh/gh-jenkins.svg?theme=badge.io)](https://david-dm.org/node-gh/gh-jenkins)

NodeGH plugin for integrating [Jenkins](http://jenkins-ci.org/), a continous integration server.

> Maintained by [Your Name](https://github.com/yourname).

## Install

```
[sudo] npm install -g gh-boilerplate
```

## Usage

```
gh boilerplate
```

> **Alias:** `gh bo`

Option             | Usage        | Type
---                | ---          | ---
`-f`, `--foo`      | **Required** | `String`

#### Examples

* **Shortcut** for showing hello world message.

	```
gh bo
	```

* Show hello world message.

	```
gh bo --foo
	```

## Testing

Check [Travis](https://travis-ci.org/node-gh/gh-jira) for continous integration results.

* Run [JSHint](http://www.jshint.com/), a tool to detect errors and potential problems.

    ```
npm run-script lint
    ```

* Run [Mocha](http://mochajs.org/), a unit test framework.

    ```
npm run-script test
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 September 12, 2013
	* Start plugin using [gh-boilerplate](https://github.com/node-gh/gh-boilerplate)

## License

[BSD License](https://github.com/node-gh/gh/blob/master/LICENSE.md)
