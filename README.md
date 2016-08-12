# Bootstrap

[![Build Status](https://travis-ci.org/bambocher/ansible-role-bootstrap.svg?branch=master)](https://travis-ci.org/bambocher/ansible-role-bootstrap)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-bambocher.bootstrap-blue.svg)](https://galaxy.ansible.com/bambocher/bootstrap/)

Ansible role that installs python2 on supported platforms.

## Supported Platforms

* Alpine
* Arch
* CentOS
* Debian
* Fedora
* Gentoo
* openSUSE
* Oracle
* Ubuntu

## Example Playbook

```yaml
- hosts: servers
  gather_facts: false
  roles:
    - bambocher.bootstrap
```

## License

[The MIT License (MIT)](LICENSE)
