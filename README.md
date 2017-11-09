ansible-mongo-elu504
====================

Install a replicated MongoDB

Requirements
------------

No specific requirements

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
