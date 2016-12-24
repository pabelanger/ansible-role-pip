================
ansible-role-pip
================

Ansible role to manage pip

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-pip.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-pip
* Bugs: https://bugs.launchpad.net/ansible-role-pip

Description
-----------

The PyPA recommended tool for installing Python packages.

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install pip
      hosts: all
      roles:
        - ansible-role-pip
