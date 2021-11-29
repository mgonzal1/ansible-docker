==============
Ansible Docker
==============

.. contents:: Table of contents:
   :local:
   :depth: 2

Playboook for automatic installation and configuration of Docker.


Supported OS
------------

- RHEL 7


Prerequisites
-------------

- Playbook should be executed from a machine with SSH access to the instances
  that will be configured. The ssh user needs sudo privileges without password.
- Fill inventory.yml file. A sample is commented for reference. Multiple hosts
  can be defined. Inventory reference:
  https://docs.ansible.com/ansible/latest/user_guide/intro_inventory.html
- Ansible needs to be >2.10. As a recommendation, create a virtual environment
  with python3 and install ansible with pip.

Usage
-----

#. Clone repository
#. Run Playboook

.. code:: bash

  $ ansible-playbook -i inventory.yml main.yml


