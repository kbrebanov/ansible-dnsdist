[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

dnsdist
=======

[![Build Status](https://travis-ci.org/kbrebanov/ansible-dnsdist.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-dnsdist)

Installs and configures dnsdist

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name            | Default | Description                   |
|:----------------|:--------|:------------------------------|
| dnsdist_version | 1.0.0   | Version of dnsdist to install |

Dependencies
------------

None

Example Playbook
----------------

Install dnsdist
```yaml
- hosts: all
  roles:
    - kbrebanov.dnsdist
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
