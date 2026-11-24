# scoop-bucket

[![Tests](https://github.com/Gigas002/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Gigas002/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Gigas002/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Gigas002/scoop-bucket/actions/workflows/excavator.yml)

Personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Usage

```pwsh
scoop bucket add gigas https://github.com/Gigas002/scoop-bucket
scoop install gigas/<manifestname>
```

## Manifests

| Name | Description |
| --- | --- |
| [acheron](https://github.com/ouwou/acheron) | An alternative Discord client with voice support made with C++ and Qt 6 Widgets |
| [concord](https://github.com/chojs23/concord) | A feature-rich TUI client for Discord |
| [cargo-deny](https://github.com/EmbarkStudios/cargo-deny) | Cargo plugin for linting your dependencies: licenses, bans, advisories and sources |
| [rust-gnu](https://www.rust-lang.org) | Rust, GNU toolchain: `main/rust-gnu` with rustfmt and clippy on PATH |

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
