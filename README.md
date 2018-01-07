# `dotfiles-role-common-software`
# `dotfiles-role-common-software`

[![Build Status](https://travis-ci.org/thecjharries/dotfiles-role-common-software.svg?branch=master)](https://travis-ci.org/thecjharries/dotfiles-role-common-software)
[![Build Status](https://travis-ci.org/thecjharries/dotfiles-role-common-software.svg?branch=master)](https://travis-ci.org/thecjharries/dotfiles-role-common-software)

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

[`dotfiles-role-package-installer` (repo)](https://github.com/thecjharries/dotfiles-role-package-installer)
[`dotfiles-role-package-installer` (repo)](https://github.com/thecjharries/dotfiles-role-package-installer)

## Example Playbook

```yml
---
- hosts: all

  roles:
    - role: dotfiles-role-common-software
    - role: dotfiles-role-common-software
```

## License

ISC
