# `dotfiles-role-common-software`

[![Build Status](https://travis-ci.org/thecjharries/dotfiles-role-common-software.svg?branch=master)](https://travis-ci.org/thecjharries/dotfiles-role-common-software)
[![GitHub tag](https://img.shields.io/github/tag/thecjharries/dotfiles-role-common-software.svg)](https://github.com/thecjharries/dotfiles-role-common-software)

## Requirements

Fedora 27 is recommended.

## Role Variables

These `vars` are set:

```yml
common_packages:
  - gcc
  - gcc-c++
  - automake
  - autoconf
  - cmake
  - pkg-config
  - openssh
  - libssh
  - libssh2
  - libssh2-devel
  - openssl
  - openssl-devel
  - libgit2
  - libgit2-devel
  # - akmod-wl
  - akmods
  - util-linux-user
  - libselinux-python
```

## Example Playbook

```yml
---
- hosts: all

  roles:
    - role: dotfiles-role-common-software
```

## License

ISC
