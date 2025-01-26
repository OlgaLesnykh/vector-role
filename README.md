vector-role
=========

The role can install Vector on Centos 7

Requirements
------------

1. Centos 7 OS  

Role Variables
--------------

|     vars       |        description          |
|----------------|-----------------------------|
| vector_version | Version of Vector to install|


Example Playbook
----------------

```yaml
- name: Install Vector
  hosts: servers
  roles:
    - role: vector-role
```


License
-------

MIT

Autor Infomation
----------------

Olga Lesnykh