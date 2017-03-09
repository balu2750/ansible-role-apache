Anrible-Role: Apache
=========

An role which install Apache on RedHat/Debian servers.

Requirements
------------

None. Purpose of this role is to perform base installation for apache with default hardenings (eg: Mozilla observatory and SSLLabs).

Role Variables
--------------

See defaults/main.yml for the variables you can overwrite via role call as a parameter.

* apache_state: latest

Dependencies
------------

None

Example Playbook
----------------

    - hosts: apache
      roles:
        - { role: CSC-IT-Center-for-Science.apache }



