andrewrothstein.dcb
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-dcb.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-dcb)

Installs a conda environment with dcb and ansible-galaxy-local-deps.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.dcb
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
