Role Name
=========

This is an Ansible role to configure sendmail with a designated smarthost variable. Role will also configure aliases file to forward all root email with admin_email variable.

Requirements
------------

None

Role Variables
--------------

smarthost:  smtp.example.com
admin_email: email@example.com

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Kade Cole - kcole@yahoo.com - https://github.com/kadecole/ansible-role-sendmail-smarthost