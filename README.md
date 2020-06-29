andrewrothstein.pomerium
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-pomerium.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-pomerium)

Installs [pomerium](https://www.pomerium.io/).

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
    - andrewrothstein.pomerium
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
