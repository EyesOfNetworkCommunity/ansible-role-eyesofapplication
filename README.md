# Ansible Role : EyesOfApplication

Ansible Role for EyesOfApplication.

Requirements
------------

CentOS 7 with minimal install.

Example Playbook
----------------

```
- name: Install EyesOfApplication for Linux
  hosts: eyesofapplication
  remote_user: ansible
  tasks:
  - import_role:
      name: eyesofapplication
      tasks_from: install
```

Author Information
------------------

* **Toréa TESSIER** - <torea.tessier@axians.com>
* **Jean-Philippe Levy** - <jean-philippe.levy@axians.com> - [EyesOfNetwork Community](https://github.com/eyesofnetworkcommunity)