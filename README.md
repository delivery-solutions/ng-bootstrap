# NG Bootstrap - Angular powered Bootstrap widgets

[![npm version](https://badge.fury.io/js/%40ng-bootstrap%2Fng-bootstrap.svg)](https://badge.fury.io/js/%40ng-bootstrap%2Fng-bootstrap)
[![Build Status](https://github.com/ng-bootstrap/ng-bootstrap/workflows/ci/badge.svg?branch=master)](https://github.com/ng-bootstrap/ng-bootstrap/actions)
[![codecov](https://codecov.io/gh/ng-bootstrap/ng-bootstrap/branch/master/graph/badge.svg)](https://codecov.io/gh/ng-bootstrap/ng-bootstrap)
[![devDependency Status](https://david-dm.org/ng-bootstrap/ng-bootstrap/dev-status.svg?branch=master)](https://david-dm.org/ng-bootstrap/ng-bootstrap#info=devDependencies)
[![Sauce Test Status](https://saucelabs.com/browser-matrix/pkozlowski.svg)](https://saucelabs.com/u/pkozlowski)

[Angular](https://angular.io/) widgets built from the ground up using only [Bootstrap 4](https://getbootstrap.com/) CSS with APIs designed for the Angular ecosystem.
No dependencies on 3rd party JavaScript.

Please check our [demo site](https://ng-bootstrap.github.io) and the list of
[issues](https://github.com/ng-bootstrap/ng-bootstrap/issues) to see all the things we are working on. Feel free to make comments there.


## Table of Contents

- [Demo](#demo)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Supported browsers](#supported-browsers)
- [Getting help](#getting-help)
- [You think you've found a bug?](#you-think-youve-found-a-bug)
- [Contributing to the project](#contributing-to-the-project)
- [Code of conduct](#code-of-conduct)

## Demo

Please check all components we have in action at https://ng-bootstrap.github.io

## Dependencies

The only two dependencies are [Angular](https://angular.io) and [Bootstrap 4](https://getbootstrap.com) CSS.
This repository publishes the separately versioned `@deliverysolutions/ng-bootstrap` fork.

For this fork, version `2.0.0` targets Angular 22. Applications that must remain on an older Angular version should use the `1.0.0` baseline and create their branch from commit `ddc49d3e`; do not upgrade those applications to fork version `2.0.0`.

| @deliverysolutions/ng-bootstrap | Angular | Bootstrap CSS |
| ------------------------------- | ------- | ------------- |
| 1.0.0                           | 15.2.x  | 4.6.1         |
| 2.0.0                           | 22.2.x  | 4.6.1         |

The Angular 22 toolchain requires Node.js `>=22.22.3`.

## Installation

Install the fork and its Bootstrap CSS dependency:

```shell
npm install @deliverysolutions/ng-bootstrap@2.0.0 bootstrap@4.6.1
```

Import the component modules you use from `@deliverysolutions/ng-bootstrap` into your Angular application modules. Do not use the upstream `@ng-bootstrap/ng-bootstrap` package for this fork.

## Supported browsers

We support the same browsers and versions supported by both Bootstrap 4 and Angular, whichever is _more_ restrictive. See [Angular browser support](https://angular.io/guide/browser-support) and [Bootstrap browser support](https://getbootstrap.com/docs/4.5/getting-started/browsers-devices/#supported-browsers) for more details.

Our code is automatically tested on all supported browsers.


## Getting help

Please, do not open issues for the general support questions as we want to keep GitHub issues for bug reports and feature requests. You've got much better chances of getting your question answered on [StackOverflow](http://stackoverflow.com/questions/tagged/ng-bootstrap) where maintainers are looking at questions tagged with `ng-bootstrap`.

StackOverflow is a much better place to ask questions since:
* there are hundreds of people willing to help on StackOverflow
* questions and answers stay available for public viewing so your question / answer might help someone else
* SO voting system assures that the best answers are prominently visible.

To save your and our time we will be systematically closing all the issues that are requests for general support and redirecting people to StackOverflow.


## You think you've found a bug?

We want to fix it ASAP! But before fixing a bug we need to reproduce and confirm it.

We ask you to respect two things:
* fill the GitHub issue template by providing the bug description and appropriate versions of Angular, ng-bootstrap and TypeScript
* provide a use-case that fails with a **minimal reproduction scenario** using [StackBlitz](https://stackblitz.com) (you can start by forking one from our [demo page](https://ng-bootstrap.github.io/#/components))

A minimal reproduction scenario allows us to quickly confirm a bug (or point out a coding problem) as well as confirm that we are fixing the right problem.

Please note that **we will be insisting on a minimal reproduce scenario** in order to save maintainers time and ultimately be able to fix more bugs. We'll mark the issue as non-actionable without it and close if not heard from the reporter.

Interestingly, from our experience users often find coding problems themselves while preparing a minimal StackBlitz. We understand that sometimes it might be hard to extract essentials bits of code from a larger code-base but we really need to isolate the problem before we can fix it.


## Contributing to the project

Please check the [DEVELOPER.md](DEVELOPER.md) for documentation on running the project locally and [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.


## Code of conduct

Please take a moment and read our [Code of Conduct](CODE_OF_CONDUCT.md)
