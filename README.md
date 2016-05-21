OpenSwan
========

Installs OpenSwan

Requirements
------------

- None


Role Variables
--------------

```
openswan_version: 2.6.47.1
openswan_makefile_path: ./files/Makefile
```


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: openswan, openswan_version: 2.6.47 }

License
-------

MIT
