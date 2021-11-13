# zinit package for [romkatv/zsh-bin](https://github.com/romkatv/zsh-bin)

Very much WIP.

## Usage

```zsh 
zinit pack for zsh-static
```

## Default Profile

Builds and installs the newest Zsh (HEAD of the Git repository).

The Zinit command that'll be run will be equivalent to:

```zsh
zinit lucid as"null" \
  from"gh-r" \
  sbin"bin/zsh*" \
  bpick"*.tar.gz" \
  nocompile \
  for @romkatv/zsh-bin
```

<!-- vim:set ft=markdown tw=80 fo+=an1 autoindent: -->
