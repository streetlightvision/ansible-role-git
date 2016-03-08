Ansible role Git
================

Install and configure git.


Role Variables
--------------

:git_rerere: enable rerere
:git_protocol_map: do protocol rewrite
:git_aliases: configure aliases


Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: slv.git, git_rerere: false }
```

License
-------

BSD
