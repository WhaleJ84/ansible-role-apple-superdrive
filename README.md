apple-superdrive
================

Installs dependencies and configures settings for the Apple SuperDrive for the user.
[Source](https://kuziel.nz/notes/2018/02/apple-superdrive-linux.html)

Requirements
------------

To include this role in your `requirements.yml` file, add the following list item:

```yaml
---
roles:
  - name: whalej84.apple-superdrive
    src: https://github.com/WhaleJ84/ansible-role-apple-superdrive.git
    scm: git
```

Example Playbook
----------------

This example playbook shows how I would use this role, with custom variables to suit my needs.

```yaml
---
- hosts: localhost

  roles:
    role: whalej84.apple-superdrive
    tags: [ apple-superdrive ]
```

