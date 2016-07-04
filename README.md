Ansible Role Grafana
====================

Fully configurable [Grafana](http://grafana.org/) installation for Debian/Ubuntu Linux.

Requirements
------------

Tested with ansible 2.1.0  
Should work for ansible >= 1.9 (usage of `become` and `become_user`)

Role Variables
--------------

Please see all the available variables [here](defaults/main.yml).


Dependencies
------------

Grafana requires you to configure a database. You can use either sqlite3, mysql or postgres.  
You should install one of these databases before running this role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: juliendufresne.grafana }

License
-------

BSD, MIT

Author Information
------------------

None for now.
