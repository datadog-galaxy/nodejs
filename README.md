NodeJS ansible role
=========

Installs needed node and npm.

Requirements
------------

Only CentOS is supported.

Role Variables
--------------

 - `version` of nodejs to install (default is 0.12)

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: datadog.nodejs, version: "v0.12.7" }

License
-------

BSD
