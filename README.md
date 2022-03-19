# asdf-circleci-cli

Circleci command line tool for adsf version manager

[![Build](https://github.com/lukeab/asdf-circleci-cli/actions/workflows/build.yml/badge.svg)](https://github.com/lukeab/asdf-circleci-cli/actions/workflows/build.yml) [![Lint](https://github.com/lukeab/asdf-circleci-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/lukeab/asdf-circleci-cli/actions/workflows/lint.yml)


# Install

Plugin:

```shell

asdf plugin add circleci https://github.com/lukeab/asdf-circleci-cli.git
```

circleci:

```shell
# Show all installable versions
asdf list-all circleci

# Install specific version
asdf install circleci latest

# Set a version globally (on your ~/.tool-versions file)
asdf global circleci latest

# Now circleci commands are available
circleci --help
```