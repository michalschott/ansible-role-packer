Ansible Role: Packer
=========

[![Build Status](https://travis-ci.org/michalschott/ansible-role-packer.svg?branch=master)](https://travis-ci.org/michalschott/ansible-role-packer)

Installs Packer on Linux amd64.

This role downloads packer from Hashicorp website, checks checksum and installs it in your system.

Requirements
------------

None.

Role Variables
--------------

Default variables:
```
packer_version: 0.12.2
packer_checksum: "sha256:035d0ea1fe785ab6b673bc2a79399125d4014f29151e106635fa818bb726bebf"
packer_path: /usr/local/bin
packer_owner: root
packer_group: root
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: packer }

License
-------

MIT

Author Information
------------------

This role was created in 2017 by [Michal Schott](http://github.com/michalschott).
