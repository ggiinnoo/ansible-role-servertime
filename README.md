Server Time
=========

Setting up server time

Requirements
------------

Centos

Role Variables
--------------

timeZone: "Europe/Amsterdam"

Dependencies
------------

None

Example Playbook
----------------

    ---
    - name: Configure server time
      hosts: all
      roles:
       - servertime

License
-------

BSD

Author Information
------------------

Creator: Gino Jansen
Website: www.ginojansen.nl