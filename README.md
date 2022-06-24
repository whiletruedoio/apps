<!--
reference: https://www.makeareadme.com/
reference: https://commonmark.org/
-->

[![Cirrus CI - Base Branch Build Status](https://img.shields.io/cirrus/github/whiletruedoio/apps?logo=Cirrus-ci)](https://cirrus-ci.com/github/whiletruedoio/apps)
[![CodeFactor](https://www.codefactor.io/repository/github/whiletruedoio/apps/badge)](https://www.codefactor.io/repository/github/whiletruedoio/apps)
[![GitHub Tag (latest SemVer)](https://img.shields.io/github/v/tag/whiletruedoio/apps?logo=GitHub&label=Release&sort=semver)](https://github.com/whiletruedoio/apps/releases)
[![Docker Image Version](https://img.shields.io/docker/v/whiletruedoio/apps?logo=Docker&label=Release&sort=semver)](https://hub.docker.com/r/whiletruedoio/apps)
[![GitHub issues](https://img.shields.io/github/issues/whiletruedoio/apps)](https://github.com/whiletruedoio/apps/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/whiletruedoio/apps)](https://github.com/whiletruedoio/apps/pulls)
[![GitHub license](https://img.shields.io/github/license/whiletruedoio/apps)](https://github.com/whiletruedoio/apps/blob/main/LICENSE)

# Apps

Apps is the application dashboard for <apps.while-true-do.io>.

## Motivation

Discovering exting services, applications, documentation and other important
links should be easy and convenient. This makes it easier for new members to
find these services and avoids maintaining bookmarks.

## Development Situation

The intention of "Apps" is to provide an easy to use dashboard. It should also
provide some quality-of-life helpers, like a web search and basic availability
checking and version display.

As long as the real application is in development, we have agreed to use a very
easy to use software, named [Homer](https://github.com/bastienwirtz/homer). It
provides ~70% of our desired features and behavior and we are really grateful
for this awesome piece of software.

Therefore, this repository only contains a re-build of the container image for
our use.

## Description

Apps is an application to provide a landing page/app overview of existing
services, applications, links and documentation.

## Usage

We are really happy, that you consider using our software. In case you want to
install and run the code on your machine, please check out this section.

### Requirements

To run the application, you need to have a container engine (like docker or
podman) installed.

### Installation

Currently, a deployment as container is supported. Our resulting build can be
found on [Docker Hub](https://hub.docker.com/r/whiletruedoio/apps). Installing
and starting the application is as easy as:

```bash
# Pull image
$ podman pull docker.io/whiletruedoio/apps

# Start container
$ podman run -dt -p 8080:8080 docker.io/whiletruedoio/apps
```

### Documentation

Afterwards, you can point your browser to the desired IP address (for example
<http://localhost:8080>) and will be presented with the dashboard. Clicking the
links should open a new tab with the service.

## Contribute

Thank you so much for considering to contribute! We are happy, when someone is
joining the hard work.

### Issues

Issues and Pull Requests are handled on a regular basis. Please be aware, that
we may reach out to you, ask you to provide additional resources or want to
discuss the issue a little, before planning it.

- [Bugs and Feature Requests](https://github.com/whiletruedoio/apps/issues)
- [Pull Requests](https://github.com/whiletruedoio/apps/pulls)

### Develop

Providing code to this repository is pretty straight forward. Open an issue,
so we can discuss the bug/feature and start working on it afterwards. You just
need to open the pull request afterwards and that's it.

It is also strongly recommended to read the
[Contribution Guideline](https://github.com/whiletruedoio/.github/blob/main/docs/CONTRIBUTING.md)
beforehand.

### Changelog

We are maintaining a [changelog](CHANGELOG.md) for repositories. Normally, the
developers will update the changelog, according to
[keepachangelog.com](https://keepachangelog.com/).

### Test

To ensure a high quality and functionality, we want to carefully test our
software. The provided code is automatically tested as described in the
[.cirrus.yml](.cirrus.yml).

## License

Except otherwise noted, all work is [licensed](LICENSE) under a
[BSD-3-Clause License](https://opensource.org/licenses/BSD-3-Clause).

## Contact

Please feel free to reach out to us and the community. We also recommend to read
and understand the
[Code of Conduct](https://github.com/whiletruedoio/.github/blob/main/docs/CODE_OF_CONDUCT.md)
beforehand.

- Site: <https://while-true-do.io>
- Blog: <https://blog.while-true-do.io>
- Code: <https://github.com/whiletruedoio>
- Chat: [Matrix](https://matrix.to/#/#whiletruedoio-community:matrix.org)
- Mail: [hello@while-true-do.io](mailto:hello@while-true-do.io)
