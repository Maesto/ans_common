Maesto Defaults
=========

Enables you to configure some almost always needed options of Ubuntu and CentOS machines.

Requirements
------------

Currently no special requirements are needed.

But with the coming nsupdate feature you'll need the dnspython package.

Role Variables
--------------

maesto_sensible_defaults_ssh_user (Default: root)

The Username for which the SSH key sould be present.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - maesto_defaults

License
-------

BSD

Author Information
------------------

Lucas Wendel <lucas.wendel@igeh.me>

