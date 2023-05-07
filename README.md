# Ansible Role: identity

[![Lint](https://github.com/dcjulian29/ansible-role-identity/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-identity/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-identity.svg)](https://github.com/dcjulian29/ansible-role-identity/issues)

This an Ansible role to manage users and groups within the OS space.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.identity
  src: https://github.com/dcjulian29/ansible-role-identity.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
