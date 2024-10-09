ansible-direnv
==============

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CI](https://github.com/jeffreyjs/ansible-direnv/actions/workflows/ci.yml/badge.svg)](https://github.com/jeffreyjs/ansible-role-direnv/actions/workflows/ci.yml)

This ansible role installs [direnv](https://github.com/direnv/direnv) on ubuntu based distros.

Requirements
------------

None

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml) for a list and description of
variables used in this role.

Example Playbook
----------------

```yaml
---
- hosts: all
  roles:
    - role: jeffreyjs.direnv
```

License
-------

MIT / BSD

Author Information
------------------

[Jeffrey Swindel](https://github.com/jeffreyjs)
