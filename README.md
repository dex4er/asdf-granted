# asdf-granted

[![CI](https://github.com/dex4er/asdf-granted/actions/workflows/ci.yml/badge.svg)](https://github.com/dex4er/asdf-granted/actions/workflows/ci.yml)

[granted](https://granted.dev/) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```shell
asdf plugin-add granted https://github.com/dex4er/asdf-granted.git
asdf install granted latest
asdf global granted latest
```

## Configuration

### Bash

Add

```shell
alias assume='source $(asdf which assume)'
```

to `~/.profile` or `~/.bashrc` or `~/.bash_profile`.

### Fish

Add

```shell
alias assume='source $(asdf which assume.fish)'
```

to `~/.config/fish/config.fish`.

## Use

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions.
