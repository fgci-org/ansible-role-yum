[![Build Status](https://travis-ci.org/CSC-IT-Center-for-Science/ansible-role-yum.svg?branch=master)](https://travis-ci.org/CSC-IT-Center-for-Science/ansible-role-yum)

ansible-role-yum
=========

Add repos. Install software from the repos that do not require any extra configuration. Software with configuration should be in new roles. 

Requirements
------------

ansible 2.1 (because yum_repository module)


Role Variables
--------------

see defaults/main.yml

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-yum }

License
-------

MIT

Author Information
------------------

