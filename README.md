# Hugo Bare
> Barebones Hugo website

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE) [![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg)](https://github.com/RichardLitt/standard-readme "RichardLitt/standard-readme")

## Table of Contents
- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [API](#api)
- [Contributing](#contributing)
- [License](#license)

## Background
This is a project to learn Hugo by building a barebones website without any generators. It will include a custom theme. Initially the project will follow [A Gentle Introduction to Creating a Minimal Hugo Site](https://arunrocks.com/minimal-hugo-site-tutorial/), though it will probably progress from there.

## Install
Clone this repository, and enter the top-level directory. `hugo server` will run the server; `hugo` will build the website for deployment.

## Usage
For development, use `hugo server -wDd dev` to [avoid building draft content in production](https://gohugo.io/getting-started/usage/#dev-vs-deploy-destinations).

For deployment, use `hugo`, then copy the contents of the `public` folder to your web root.

## Contributing
> Contributors to this project are expected to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md "Code of Conduct").

I welcome [issues](docs/issue_template.md "Issue template"), but I prefer [pull requests](dosc/pull_request_template.md "Pull request template")! See the [contribution guidelines](docs/contributing.md "Contributing") for more information.

## License
Copyright ©2019 nstickney. This repository is released under the [MIT](LICENSE) license.
