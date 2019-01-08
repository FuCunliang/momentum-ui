# @collab-ui

[![CircleCI](https://img.shields.io/circleci/project/github/collab-ui/collab-ui/master.svg)](https://circleci.com/gh/collab-ui/collab-ui/)
[![license](https://img.shields.io/github/license/collab-ui/collab-ui.svg)](https://github.com/webex/react-ciscospark/blob/master/LICENSE)
[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lernajs.io/)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)


> Collab UI

Collab UI is a collection of UI libraries for implementing [Momentum Design](https://momentum.design) into web applications and websites.

## Table of Contents

- [Background](#background)
- [Usage](#usage)
- [Reqirements](#requirements)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)

## Background

These libraries allow web developers to quickly and easily create Momentum Design web apps and sites. We provide libraries built on HTML/CSS and many of the modern JavaScript frameworks, including [ReactJS](https://reactjs.org/), [Angular](https://angular.io/) and [AngularJS](https://angularjs.org/). We use a [Lerna](http://lernajs.io) monorepo to manage all of the libraries in one repository.

## Usage

The individual libraries are distributed through [npm](https://www.npmjs.com/search?q=collab-ui). You can find information on usage and installation in each of their individual README files.
- [@collab-ui/core](/core/README.md)
- [@collab-ui/react](/react/README.md)
- [@collab-ui/icons](/icons/README.md)

## Requirements

To contribute to @collab-ui, you need to have [>=Node 8.10.0](https://nodejs.org/en/) and [Yarn](https://yarnpkg.com/en/) installed globally on your machine.

## Development

Setting up your development environment:

1. Clone this repo using a git client (e.g. `git clone https://github.com/collab-ui/collab-ui.git`)
1. Run `yarn install` from the root of the repo.
1. Run `yarn bootstrap` from the root of the repo.
1. Run `yarn run:all` to start the playground app for all libraries or `yarn run:<library>` to only start the library the you are working in.


## Contributing

PRs are welcome! See [CONTRIBUTING](CONTRIBUTING.md) for details.

## License

&copy;2013-2019 Cisco Systems, Inc. and/or its affiliates. All Rights Reserved.

See [LICENSE](LICENSE) for details.
