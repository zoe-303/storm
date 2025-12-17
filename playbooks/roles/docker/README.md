Role Name
=========

Installs and configures Docker engine.

Requirements
------------

- Internet access
- Debian or Ubuntu 
    - both treated differently here as this role was origionally written for Debian Bookworm, which is now old stable and I've moved to Ubuntu. I've duplicated the tasks file so that ansible can pick the appropriate one dynamically. 
Despite them being very similar, I would rather tie roles to the lifecylce of the host and I have different usecases for Debian than I do Ubuntu. YMMV. 

Role Variables
--------------


Dependencies
------------


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
