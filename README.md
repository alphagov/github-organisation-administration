# `GitHub Repository Contributor Search`

Use GitHub REST API v3 to find repositories where specific users have contributed.

> ℹ️ Where this documentation refers to the **root folder** we mean where this README.md is located.

- [Getting started](#getting-started)
  - [Requirements](#requirements)
- [Required secrets and credentials](#required-secrets-and-credentials)
- [Licence](#licence)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Getting started

To be added.

### Requirements

- A `.secrets` file with the [required secrets and credentials](#required-secrets-and-credentials)
- [Load environment variables][docs-loading-environment-variables] from `.envrc`

To be added.

## Required secrets and credentials

To run this project, you need a `.secrets` file with secrets/credentials as environmental variables; see the
[documentation][docs-loading-environment-variables-secrets] for further guidance. The secrets/credentials should have
the following environment variable name(s):

| Secret/credential            | Environment variable name | Description                                                      |
|------------------------------|---------------------------|------------------------------------------------------------------|
| GitHub personal access token | `GITHUB_API_TOKEN`        | See [here][github-personal-access-token] for further information |
| GitHub organisation name     | `GITHUB_ORGANISATION`     | The GitHub organisation name, e.g. `ukgovdatascience`            |

Once you've added these environment variables to `.secrets` you will need to
[load them via `.envrc`][docs-loading-environment-variables].

## Licence

Unless stated otherwise, the codebase is released under the MIT License. This covers both the codebase and any sample
code in the documentation. The documentation is © Crown copyright and available under the terms of the Open Government
3.0 licence.

## Contributing

If you want to help us build, and improve `GitHub Repository Contributor Search`, view our
[contributing guidelines][contributing].

## Acknowledgements

This project structure is based on the `govcookiecutter` template project.

[contributing]: ./CONTRIBUTING.md
[github-personal-access-token]: https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/creating-a-personal-access-token
[govcookiecutter]: https://github.com/ukgovdatascience/govcookiecutter
[docs-loading-environment-variables]: ./docs/user_guide/loading_environment_variables.md
[docs-loading-environment-variables-secrets]: ./docs/user_guide/loading_environment_variables.md#storing-secrets-and-credentials
[pre-commit]: https://pre-commit.com/
