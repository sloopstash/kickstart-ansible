Role Name
=========

This is redis role, which will is used to configure and install redis from package to the remote machines.

Requirements
------------
No requirements needed for this role.

Role Variables
--------------

  Default:
  --------
  confdir: # All configuration files are in this path
  logsdir: # All log files are in this path
  datadir: # Your data directory
  systemdir: # System directory for run the process

  Vars:
  -----
  version: # configure redis version over here

Dependencies
------------
No dependencies required.

Example Playbook
----------------
Mentioned the below snippet in your playbooks.

Ex:
  - hosts: servers
    roles:
      - redis

License
-------

BSD

Author Information
------------------
This is module created by authername

