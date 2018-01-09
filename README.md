Configure Vultr private network
===============================

An Ansible Role that configures Vultr private network.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
network_private_ip: 10.10.10.10
```

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: web
      roles:
        - role: vultr-network

License
-------

MIT

