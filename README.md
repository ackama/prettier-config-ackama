# Ackama Prettier Configuration

Standard Prettier configuration for Ackama projects.

#### Usage

Install this package:

    npm install --save-dev prettier-config-ackama

Then add the following to your `package.json`:

    "prettier": "prettier-config-ackama",

### Versioning

Versioning is modeled after [semantic versioning](https://semver.org/); however,
because of the nature of Prettier most configuration changes could be considered
breaking.

As such, we consider general configuration changes to be _minor features_, and
release them as such.

### Releasing

Releases are handled using
[semantically](https://github.com/semantic-release/semantic-release).

#### Contributing

This repo uses
[convectional commits](https://www.conventionalcommits.org/en/v1.0.0/) to enable
semantic releases & changelog generation. Please make sure to follow that when
committing.
