ruby
====

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-kbrebanov.ruby-660198.svg)](https://galaxy.ansible.com/list#/roles/3932)

Installs Ruby

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name         | Default | Description                |
|--------------|---------|----------------------------|
| ruby_version | 2.2.2   | Version of Ruby to install |

Dependencies
------------

- kbrebanov.git

Example Playbook
----------------


Install Ruby
```
- hosts: all
  roles:
    - { role: kbrebanov.ruby }
```

Install older version of Ruby
```
- hosts: all
  roles:
    - { role: kbrebanov.ruby, ruby_version: 2.2.1 }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
