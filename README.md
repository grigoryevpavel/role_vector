Role Name
=========

roles-vector

Description
------------

Role installs vector server. 

Role Variables
--------------

| Variable name | Variable description                                |
|---------------|-----------------------------------------------------|
| vector_dest   | Template directory for storing installation scripts | 
| vector_port   | Port number on which was started vector             | 
| vector_user   | Account under which was installed vector. Must have root permissions|

How to install in subfolder **roles** of current project folder
---------------

ansible-galaxy role install --roles-path ./roles git+https://github.com/grigoryevpavel/roles-vector.git

How to use role
----------------

  - hosts: servers
    roles:
        - { role: roles-vector }

License
-------

MIT

Author Information
------------------

Pavel Grigoryev


