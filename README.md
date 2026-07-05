# homebrew-cc-select

Homebrew tap for [cc-select](https://github.com/matiastang/cc-select).

## Install

```bash
brew tap matiastang/cc-select
brew install cc-select
```

## Upgrade

```bash
brew update
brew upgrade cc-select
```

## Uninstall

```bash
brew uninstall cc-select
brew untap matiastang/cc-select
```

## After installation

Enable shell integration by running:

```bash
cc-select init >> ~/.zshrc   # or ~/.bashrc for bash
```

Then reload your shell or run `source ~/.zshrc`.

## About cc-select

cc-select is a CLI for shell-level (per-terminal) isolation of AI model providers for Claude Code.

- Main repository: https://github.com/matiastang/cc-select
- Releases: https://github.com/matiastang/cc-select/releases

> This tap is automatically updated by GoReleaser on every cc-select release.
