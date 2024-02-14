Role Name
=========

role_vector

Description
------------

Role installs vector server. 

Role Variables
--------------

| Variable name | Variable description                                               |
|---------------|--------------------------------------------------------------------|
| vector_dest   | Template directory for storing installation scripts                | 
| vector_port   | Port number on which is started vector                             | 
| vector_user   | Account under which is installed vector. Must have root permissions|

How to install in subfolder **roles** of current project folder
---------------

ansible-galaxy role install --roles-path ./roles git+https://github.com/grigoryevpavel/roles-vector.git

How to use role
----------------

  - hosts: servers
    roles:
        - { role: role_vector }

License
-------

MIT

Author Information
------------------

Pavel Grigoryev


