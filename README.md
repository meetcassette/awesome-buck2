# Awesome Buck2 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[Buck2](https://buck2.build/) is a build system developed by Meta for large-scale, polyglot software repositories, with Starlark configuration and support for remote execution.

## Contents

- [Core](#core)
- [Starlark](#starlark)
- [Rules](#rules)
- [Remote Caching and Execution](#remote-caching-and-execution)
- [Tools](#tools)
- [Projects](#projects)
- [Articles](#articles)
- [Community](#community)

## Core

- [Buck2](https://github.com/facebook/buck2) - Source code for the Buck2 build system.
- [Getting Started](https://buck2.build/docs/getting_started/) - Introduction to installing Buck2, creating a project, and running a build.

## Starlark

- [Starlark](https://github.com/bazelbuild/starlark) - Go implementation of the Starlark language.
- [Starlark Language](https://bazel.build/rules/language) - Language reference for the configuration language used by Buck2.
- [Starlark Rust](https://github.com/facebook/starlark-rust) - Rust implementation of the Starlark language used by Buck2.

## Rules

- [Buck2 Prelude](https://github.com/facebook/buck2-prelude) - Standard library of Buck2 build rules and toolchain definitions.
- [Wasmono](https://github.com/andreiltd/wasmono) - Buck2 rules and toolchains for building WebAssembly components.

## Remote Caching and Execution

- [Remote Execution APIs](https://github.com/bazelbuild/remote-apis) - Protocol definitions for remote caching and execution of builds.

## Tools

- [Antlir](https://github.com/facebookincubator/antlir) - Reproducibly builds, tests, and runs operating system images with Buck2.
- [Buck2 Change Detector](https://github.com/facebookincubator/buck2-change-detector) - Identifies build targets affected by a set of changed files.
- [Buckle](https://github.com/benbrittain/buckle) - Version manager and launcher for Buck2.
- [Install Buck2](https://github.com/dtolnay/install-buck2) - GitHub Action for installing a precompiled Buck2 binary.
- [Reindeer](https://github.com/facebookincubator/reindeer) - Generates Buck build rules from Rust crates.
- [Snowydeer](https://github.com/MercuryTechnologies/snowydeer) - Integrates Nix dependencies and closures with Buck2 builds.

## Projects

- [Buck2 Erlang Demo](https://github.com/TheGeorge/buck2_erlang_demo) - Example project that builds an Erlang application with Buck2.
- [Buck2 Rustc Bootstrap](https://github.com/dtolnay/buck2-rustc-bootstrap) - Builds the Rust compiler with Buck2.
- [OCamlrep](https://github.com/facebook/ocamlrep) - OCaml and Rust interoperability libraries built with Buck2.

## Articles

- [Build Systems a la Carte](https://www.microsoft.com/en-us/research/wp-content/uploads/2018/03/build-systems-final.pdf) - Academic framework for understanding and comparing build systems.
- [Buck2: Open-source Large-scale Build System](https://www.tweag.io/blog/2023-07-06-buck2/) - Overview of Buck2's architecture and initial open-source release.
- [Integrating Nix and Buck2](https://www.tweag.io/blog/2025-07-31-buck2-nix/) - Approach to handling non-hermetic dependencies in local Buck2 builds with Nix.
- [Awesome Buck2 by Si L.](https://github.com/sluongng/awesome-buck2#readme) - Earlier collection of Buck2 resources and open-source projects built by Meta.

## Community

- [Buck2 Fans](https://discord.gg/bgJqEmXCx) - Community Discord server for Buck2 users.
