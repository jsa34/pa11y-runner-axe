
# Pa11y aXe Runner

An [aXe](https://www.axe-core.org/) runner for [Pa11y](https://github.com/pa11y/pa11y).

[![NPM version][shield-npm]][info-npm]
[![Build status][shield-build]][info-build]
[![LGPL-3.0 licensed][shield-license]][info-license]


## Table Of Contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)


## Requirements

The Pa11y aXe Runner is compatible with Pa11y 5.0. It will not work with older versions of Pa11y.


## Usage

Install Pa11y and the Pa11y aXe Runner with [npm](https://www.npmjs.com/) (locally or globally is fine):

```sh
npm install -g pa11y pa11y-runner-axe
```

Run Pa11y using the aXe runner:

```sh
pa11y --runner axe http://example.com
```


## Contributing

There are many ways to contribute to the Pa11y aXe Runner, we cover these in the [contributing guide](CONTRIBUTING.md) for this repo.

If you're ready to contribute some code, clone this repo locally and commit your code on a new branch.

Please write unit tests for your code, and check that everything works by running the following before opening a <abbr title="pull request">PR</abbr>:

```sh
make ci
```

You can also run verifications and tests individually:

```sh
make verify              # Verify all of the code (ESLint)
make test                # Run all tests
make test-unit           # Run the unit tests
make test-unit-coverage  # Run the unit tests with coverage
```


## License

The Pa11y aXe Runner is licensed under the [Lesser General Public License (LGPL-3.0)][info-license].<br/>
Copyright &copy; 2018, Team Pa11y


[info-license]: LICENSE
[info-npm]: https://www.npmjs.com/package/pa11y-runner-axe
[info-build]: https://travis-ci.org/pa11y/pa11y-runner-axe
[shield-license]: https://img.shields.io/badge/license-LGPL%203.0-blue.svg
[shield-npm]: https://img.shields.io/npm/v/pa11y-runner-axe.svg
[shield-build]: https://img.shields.io/travis/pa11y/pa11y-runner-axe/master.svg
