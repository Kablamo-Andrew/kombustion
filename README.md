## Kombustion

> A CloudFormation template generator, written in Go.

## What is it

Kombustion generates your CloudFormation templates using an extended version of vanilla CloudFormation YAML templates.

Unlike Terraform or Troposphere, it does not rely on a knowledge of a specific DSL or require you to write code. Instead, it allows template designers to use custom CloudFormation types provided by a plugins system to write lean YAML-based stacks.

It also provides all the necessary tools to create, update and delete your stacks.

See the [Quick start](docs/quickstart.md) for more details.

## Features

* Written in Go, for simplicity and speed
* Cross-platform
* Compatible with vanilla CloudFormation templates
* Extendable with plugins
* Automatic support for new CloudFormation types as they are released ([how?](docs/generation.md))

## Examples

Check out the [configs](https://github.com/KablamoOSS/Kombustion/configs/) directory for examples.

## Maintainers

Kombustion is primarily maintained by the [Kablamo](https://www.kablamo.com.au/) team. Pull requests are welcome.

Made with :heart: in Australia.