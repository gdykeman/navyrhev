Role Name
=========

Role to deploy VM's into a RHEV environment.

Requirements
------------

Define a vars file and pass it in as extra vars or include it within the vars/main.yml file.


Role Variables
--------------

Variables that need to be set:
rhev: (username for accessing the RHEV environment)
pass: (password for accessing the RHEV environment)

rheluser: (username of user you want to add with the VM)
rhelpass: (password of user you want to add with the VM)

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

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
