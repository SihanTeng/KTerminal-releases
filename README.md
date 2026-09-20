# KTerminal

Native macOS terminal and project workbench with a shared Rust terminal engine,
tabs, a file editor, Git panels, and sessions for coding CLIs and SSH.

This repository hosts signed release binaries and installation instructions.
The development repository is maintained separately.

## Install with Homebrew

```sh
brew install --cask SihanTeng/tap/kterminal
```

Requires **Apple Silicon** and **macOS 14 (Sonoma) or later**. The current release
does not include an Intel build.

The app is signed with a Developer ID Application certificate and notarized by
Apple. The download includes a stapled notarization ticket. Homebrew verifies
the archive's SHA-256 checksum and installs `KTerminal.app` in `/Applications`.

## Install manually

Download `KTerminal-VERSION-macos-arm64.zip` from
[Releases](https://github.com/SihanTeng/KTerminal-releases/releases), unzip it,
and drag `KTerminal.app` into Applications. A `.sha256` sidecar is included for
checksum verification.

## Update

```sh
brew update
brew upgrade --cask SihanTeng/tap/kterminal
```

## Report a problem

Use this repository's [issue tracker](https://github.com/SihanTeng/KTerminal-releases/issues)
and include your macOS version, KTerminal version, and steps to reproduce. Remove
secrets and private terminal output before attaching logs or screenshots.

KTerminal is distributed under the [MIT license](LICENSE).
