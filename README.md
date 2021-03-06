iorchard.cilium
===============

Ansible role for cilium CNI plugin installation

Requirements
------------

This role requires Ansible 2.10 or higher.

This role supports:

  - Ubuntu 20.04
  - Debian 11 (bullseye)

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    hosts: servers
    roles:
      - { role: iorchard.cilium, tags: cilium }

License
-------

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

  - Heechul Kim @iOrchard
      - <https://github.com/iorchard>

