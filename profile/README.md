# Oxide Language

The Oxide Language Organization manages the development of the Oxide programming language and its related tools. Oxide aims to be a modern, efficient, and reliable systems programming language with a well-structured toolchain and a clear development workflow.

## Overview

This organization contains the official repositories for the Oxide language ecosystem. Each project serves a specific purpose within the toolchain.

### oxidec: Compiler

The primary compiler for the Oxide language.

* Written in C++
* Performs parsing, semantic analysis, and code generation
* Licensed under GPLv3

### oxide: Command Line Interface

A user-facing CLI that provides a simple interface for compiling and managing Oxide projects.

* Calls the oxidec compiler internally
* Offers commands such as build, run, format, and others
* Licensed under GPLv3

### oxcore: Standard Library

The standard library for the Oxide language.

* Provides core types and utilities
* Designed to be lightweight and modular
* Licensed under the MIT License

### oxlint: Linter and Formatter

A tool for enforcing coding style and ensuring consistent formatting across Oxide projects.

* Helps maintain clean and readable code
* Licensed under GPLv3

## Project Goals

The Oxide language is designed with several key objectives:

* A clean and readable syntax
* High performance suitable for systems programming
* A complete and reliable toolchain
* An open development model that encourages community involvement

## Installation

Installation instructions will be provided once the toolchain reaches a stable release. A typical usage flow will look like:

```
oxide -o main main.ox
```

The oxide executable will invoke oxidec internally to perform the actual compilation.

## Roadmap

The following items represent the planned development direction:

* Parser and AST implementation
* Semantic analysis
* Code generation backend
* Expanded standard library
* Package manager support in the CLI
* Oxide-X tooling development
* Full documentation and website

## Contributing

Contributions are welcome.
Before contributing, please review the contribution guidelines once they are published. Code submitted to this repository should follow the formatting and linting rules enforced by oxlint.

## Licensing

Licensing varies across projects:

* oxidec, oxide, and oxlint are distributed under GPLv3
* oxcore is distributed under the MIT License

Refer to individual repositories for complete license information.

## Summary

The Oxide Language Organization exists to build a modern programming language and a complete ecosystem of tools around it. The project is under active development, and community participation is encouraged.
