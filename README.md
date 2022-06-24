# tfmod-template

<!-- Delete this section when using the template repository -->

This is the template repository for my terraform modules.

It is designed to speed up development of new terraform modules by providing:

1. basic terraform setup for backend, providers, _etc_.
1. common pre-commit hooks configuration
1. semantic release configuration
1. examples directory for testing and demonstration
1. default github actions workflows for testing and releasing

## How to use

<!-- Delete this section when using the template repository -->

If you want to make a new terraform module from scratch:

1. create a new repository using this one as template
1. delete the sections commented with `<!-- Delete this section when using the template repository -->`
1. update `terraform.tf` to declare the module's required providers
1. add the examples you need in `examples/<your example>`
1. update the test workflow in `.github/workflows/test.yml` to reflect your examples

## Pre-commit hooks

<!-- Edit this section or delete if you make no change  -->

The [pre-commit](https://pre-commit.com) framework is used to manage pre-commit hooks for this repository.
A few well-known hooks are provided to cover correctness, security and safety in terraform.

## Examples

The `examples/` directory contains the example usage of this module.
These examples show how to use the module in your project, and are also use for testing in CI/CD.

<!--

Modify this section according to the kinds of examples you want
You may want to change the names of the examples or the kinds of 
examples themselves

-->
