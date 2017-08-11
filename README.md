Ansible Role: Smarthost
=========

[![Build Status](https://travis-ci.org/kadecole/ansible-role-smarthost.svg?branch=master)](https://travis-ci.org/kadecole/ansible-role-smarthost)

This is an Ansible role to configure sendmail/postfix with a designated smarthost variable. Role will also configure aliases file to forward all root email with admin_email variable.

Requirements
------------

None

Role Variables
--------------
```
smarthost:  smtp.example.com
admin_email: email@example.com
```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers

      vars:
       smarthost: smtp.example.com
       admin_email: me@example.com

      roles:
         - { role: ansible-role-smarthost }

License
-------

BSD

Author Information
------------------

Kade Cole - https://github.com/kadecole/ansible-role-smarthost
