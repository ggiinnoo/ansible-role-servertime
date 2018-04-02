[![Build Status](https://travis-ci.org/ggiinnoo/ansible-servertime.svg?branch=release%2F1.0.x)](https://travis-ci.org/ggiinnoo/ansible-servertime)

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
