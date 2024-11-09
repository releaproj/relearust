# ReleaRust
ReleaRust destroy the misery for publishing a release to GitHub, crates.io and/or WinGet, by automating anything to do for publishing binaries to GitHub Releases/crates.io/WinGet

> [!NOTICE]
> ReleaRust is still under development. So it is not designed for production use. Contributions are welcome!

## Table of Content
| Header | Subheader (I don't know it's correct) |
| -------- | --------------------------------------- |
| [Features](#features) | ----------------------------------- |
| [Requirements](#requirements) | [Requirements for publishing to GitHub](#requirements-for-publishing-to-github) |
| ------------ | [Requirements for publishing to crates.io](#requirements-for-publishing-to-cratesio) |
| ------------ | [System requirements](#system-requirements) |
| [Installation](#installation) | [Cargo](#cargo) |
| ------------ | [Prebuilt Binaries](#prebuilt-binaries) |
| ------------ | [Winget](#winget) |
| [Inspiration](#inspiration) | ------- |

## Features
- [ ] OS Support
 - [ ] Windows
 - [ ] Mac
 - [ ] Linux
- [ ] App hosting platform/Package manager
 - [ ] GitHub
 - [ ] crates.io
 - [ ] WinGet
 - [ ] Homebrew

## Requirements
### Requirements for publishing to GitHub
- A GitHub account. Create one by going to [Sign up page](https://github.com/signup)

You have 2 ways to publish binary to GitHub:

- Using [GitHub CLI](https://cli.github.com)
- Publishing releases with [GitHub REST API](https://docs.github.com/en/rest) (DEFAULT)

### Requirements for publishing to crates.io
- A GitHub account
- A crates.io account. Create one by going to [crates.io](https://crates.io) and clicking on `Sign in with GitHub`

You have 2 ways to publish binary to GitHub:

- Using [GitHub CLI](https://cli.github.com)
- Publishing releases with [GitHub REST API](https://docs.github.com/en/rest) (DEFAULT)

### System requirements
- Rust installation if you want to install with Cargo or build from source
- Supported platform (Fortunately, all platforms are supported by ReleaRust)

## Installation
### Cargo
Run this command to install it from [crates.io](https://crates.io/crate/relearust):
```shell
cargo install relearust
```

### Prebuilt Binaries
Download it from [GitHub Releases](https://github.com/releaproj/relearust/releases)

### WinGet
Not avaliable on WinGet, yet, but you can install it with this command when it's avaliable:
```shell
winget install ReleaProj.ReleaRust
```

## Inspiration
Inspired by [goreleaser](https://goreleaser.com) and [rustreleaser](https://github.com/rustreleaser-org/rust-releaser)