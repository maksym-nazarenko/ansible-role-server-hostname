Ansible role: server-hostname
=============================

An Ansible role for updating Linux hostname.

Requirements
------------

`hostname` command in the PATH on the remote server.

Role Variables
--------------

    server_hostname: "{{ inventory_hostname }}"

The name to be set up on the remote server.


Dependencies
------------

No dependencies.

Example Playbook
----------------
```yaml
    - hosts: all
      roles:
         - role: server-hostname
```

License
-------

MIT

Author Information
------------------

Maxim Nazarenko <maxim.nazarenko@onix-systems.com>

github: https://github.com/maxim-nazarenko
