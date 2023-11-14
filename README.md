Role Name
=========

vector-role

Requirements
------------

Role installs vector server on EL. 

Role Variables
--------------

| Variable name | Variable description                                |
|---------------|-----------------------------------------------------|
| vector_dest   | Template directory for storing installation scripts | 
| vector_port   | Port number on which was started vector             | 
| vector_user   | Account under which was installed vector. Must have root permissions|
 
How to use role
----------------

  - hosts: servers
    roles:
        - { role: vector-role }

License
-------

MIT

Author Information
------------------

Pavel Grigoryev


