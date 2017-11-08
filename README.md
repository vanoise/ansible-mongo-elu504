Ansible Mongo for ELU 504
=========================

Install a replicated MongoDB

Requirements
------------

No specific requirements

Role Variables
--------------

mongo_db_user

Dependencies
------------

No dependencies

Example Playbook
----------------

mongodb_security_authorization: "enabled"
mongodb_users:
  - {
    name: testUser,
    password: passw0rd,
    roles: readWrite,
    database: app_development
}

License
-------

BSD

Author Information
------------------

No particular contact
