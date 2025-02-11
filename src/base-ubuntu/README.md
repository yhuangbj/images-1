# Ubuntu

## Summary

*A simple Ubuntu container with Git and other common utilities installed.*

| Metadata | Value |  
|----------|-------|
| *Categories* | Core, Other |
| *Image type* | Dockerfile |
| *Published images* | mcr.microsoft.com/devcontainers/base:ubuntu |
| *Available image variants* | ubuntu-22.04 / jammy, ubuntu-20.04 / focal, ubuntu-18.04 / bionic ([full list](https://mcr.microsoft.com/v2/devcontainers/base/tags/list)) |
| *Published image architecture(s)* | x86-64, aarch64/arm64 for `ubuntu-22.04` (`jammy`) and `ubuntu-18.04` (`bionic`) variants  |
| *Container host OS support* | Linux, macOS, Windows |
| *Container OS* | Ubuntu |
| *Languages, platforms* | Any |

See **[history](history)** for information on the contents of published images.

## Using this image

You can directly reference pre-built versions of `Dockerfile` by using the `image` property in `.devcontainer/devcontainer.json` or updating the `FROM` statement in your own `Dockerfile` to one of the following. An example `Dockerfile` is included in this repository.

- `mcr.microsoft.com/devcontainers/base:ubuntu` (latest LTS release)
- `mcr.microsoft.com/devcontainers/base:ubuntu-22.04` (or `jammy`)
- `mcr.microsoft.com/devcontainers/base:ubuntu-20.04` (or `focal`)
- `mcr.microsoft.com/devcontainers/base:ubuntu-18.04` (or `bionic`)

You can decide how often you want updates by referencing a [semantic version](https://semver.org/) of each image. For example:

- `mcr.microsoft.com/devcontainers/base:0-focal`
- `mcr.microsoft.com/devcontainers/base:0.203-focal`
- `mcr.microsoft.com/devcontainers/base:0.203.0-focal`

See [history](history) for information on the contents of each version and [here for a complete list of available tags](https://mcr.microsoft.com/v2/devcontainers/base/tags/list).

Alternatively, you can use the contents of the `Dockerfile` to fully customize your container's contents or to build it for a container host architecture not supported by the image.

Beyond `git`, this image / `Dockerfile` includes `zsh`, [Oh My Zsh!](https://ohmyz.sh/), a non-root `vscode` user with `sudo` access, and a set of common dependencies for development.

## License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the MIT License. See [LICENSE](https://github.com/devcontainers/images/blob/main/LICENSE)
