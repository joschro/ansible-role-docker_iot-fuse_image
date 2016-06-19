docker_iot-fuse_image
=====================

Ansible role to set up a Fuse docker container for the IoT gateway.

Requirements
------------
None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------
```
- name: NAME
  hosts: dockerhosts
  remote_user: root

  roles:
    - ROLE
```
with an inventory file like this for example:
```
[dockerhosts]
dockerhost ansible_ssh_host=<above-ip-address> ansible_ssh_user=root
```

License
-------

GPLv3

Author Information
------------------

Joachim Schröder, jos (at) redhat.com
