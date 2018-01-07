# `dotfiles-common-software`

[![Build Status](https://travis-ci.org/thecjharries/dotfiles-common-software-role.svg?branch=master)](https://travis-ci.org/thecjharries/dotfiles-common-software-role)

## Requirements

Fedora 27 is recommended.

## Role Variables

These `vars` are set:

```yml
needed_packages:
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

## Dependencies

[`dotfiles-package-installer-role` (repo)](https://github.com/thecjharries/dotfiles-package-installer-role)

## Example Playbook

```yml
---
- hosts: all

  roles:
    - role: dotfiles-common-software-role
```

## License

ISC
