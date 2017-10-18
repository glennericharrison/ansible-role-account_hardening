Role Name
=========

This role is used for hardening local accounts through password complexity/expiration using pamd and login.defs

Requirements
------------

None

Role Variables
--------------
backup_dir: Backup directory for files to be modified. 
minlenVar: The minimum length of the password.
maxdaysVar: The maximum password age before expiration.
dcreditVar: The credit value for digits in the password. A value of -1 indicates at least 1 digit is required in the password.
ucreditVar: The credit value for uppercase characters in the password. A value of -1 indicates at least 1 uppercase character is required in the password. 
lcreditVar: The credit value for lowercase character in the password. Avalue of -1 indicates at least 1 lowercase character is required in the password.
ocreditVar: The credit value for other characters in the password. A value of -1 indicates at least 1 special character is required in the password. 

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

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
