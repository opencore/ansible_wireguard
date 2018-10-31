Wireguard
=========

This Ansible role can be used to set up Wireguard VPN between a list of hosts.
This is useful if you need to connect hosts securely over an insecure network.


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.


Example Playbook
----------------

This is how the role can be used:

    - hosts: servers
      roles:
        - wireguard

License
-------

Apache license version 2

Author Information
------------------

Created by [OpenCore GmbH & Co. KG](https://www.opencore.com)