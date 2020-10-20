# Tranquility.one Minecraft Server
> The Tranquility.one website

[![license: CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC_BY--NC--SA_4.0-blue)](LICENSE)
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen)](https://github.com/RichardLitt/standard-readme "RichardLitt/standard-readme")

## Table of Contents
- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Background
The [Tranquility](https://tranquility.one) Minecraft server was built after the [Serenity](https://serenity-mc.org) server was closed. This repository holds the server website, a simple Hugo build.

## Install
Clone this repository, and enter the top-level directory. `hugo server` will run the server; `hugo` will build the website for deployment.

## Usage
For development, use `hugo server -wDd dev` to [avoid building draft content in production](https://gohugo.io/getting-started/usage/#dev-vs-deploy-destinations).

For deployment, use `hugo`, then copy the contents of the `public` folder to your web root.

## Contributing
> Contributors to this project are expected to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md "Code of Conduct").

I welcome [issues](docs/issue_template.md "Issue template"), but I prefer [pull requests](dosc/pull_request_template.md "Pull request template")! See the [contribution guidelines](docs/contributing.md "Contributing") for more information.

## License

©2019 [StickFig](admin@tranquility.one).
Where not otherwise specified, this repository is licensed under the [CC BY-NC-SA 4.0](LICENSE) license.
