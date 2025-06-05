# asdf-granted

[![CI](https://github.com/dex4er/asdf-granted/actions/workflows/ci.yml/badge.svg)](https://github.com/dex4er/asdf-granted/actions/workflows/ci.yml)

[granted](https://granted.dev/) plugin for the
[asdf](https://github.com/asdf-vm/asdf) or [mise](https://mise.jdx.dev/)
version managers.

## Install

```shell
asdf plugin-add granted https://github.com/dex4er/asdf-granted.git
asdf install granted latest
asdf global granted latest
```

or

```shell
mise plugins install granted https://github.com/dex4er/asdf-granted.git
mise use -g granted
```

## Configuration

### Bash

Add

```shell
alias assume='source $(asdf which assume)'
```

or

```shell
alias assume='source $(mise which assume)'
```

to `~/.profile` or `~/.bashrc` or `~/.bash_profile` or `~/.zshrc`.

### Fish

Add

```shell
alias assume='source $(asdf which assume.fish)'
```

or

```shell
alias assume='source $(mise which assume.fish)'
```

to `~/.config/fish/config.fish`.

## Use

Check out the [asdf](https://asdf-vm.com/) or
[mise](https://mise.jdx.dev/) for instructions.
