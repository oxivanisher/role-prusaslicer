prusaslicer
===========
[![Ansible Lint](https://github.com/oxivanisher/role-prusaslicer/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-prusaslicer/actions/workflows/ansible-lint.yml)

This role installs the PrusaSlicer app as flatpak.

Role Variables
--------------

None.

Example Playbook
----------------
```yaml
- name: Install PrusaSlicer
  hosts: clients
  roles:
    - role: oxivanisher.linux_desktop.prusaslicer
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_desktop](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_desktop/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_desktop).
