==================
ansible-role-nginx
==================

Ansible role to manage Nginx

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-nginx.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-nginx
* Bugs: https://bugs.launchpad.net/ansible-role-nginx

Description
-----------

NGINX is a free, open-source, high-performance HTTP server and reverse proxy, as
well as an IMAP/POP3 proxy server. NGINX is known for its high performance,
stability, rich feature set, simple configuration, and low resource consumption.

Requirements
------------

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install nginx
      hosts: nginx
      roles:
        - ansible-role-nginx
