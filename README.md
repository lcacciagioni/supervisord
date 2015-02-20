supervisord
===========

[![Build Status](https://travis-ci.org/lcacciagioni/supervisord.svg?branch=master)](https://travis-ci.org/lcacciagioni/supervisord)

This role will install & configure [supervisord](http://supervisord.org/) in any of the specified OS. Using the corresponding repositories, this implies that only system versions will be installed or EPEL in CentOS case.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

You just simply need to include this role in your playbook, no vars needs to be declared.

```yaml
- hosts: all
  roles:
  - lcacciagioni.supervisord
```

License
-------

GPLv3

Author Information
------------------

Leandro David Cacciagioni - < leandro.21.2008@gmail.com >
