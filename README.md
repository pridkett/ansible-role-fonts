ansible-role-fonts
==================

An incredible simple role for setting up `/etc/fonts/local.conf`

Overview
--------

This is primarily designed for situations when you want to automate the provisioning for WSL2 hosts and need to set up `/etc/fonts/local.conf` to share fonts with Windows. Why would you need to do this if WSL2 is primarily text based? Well, you might be like me and have [X410](https://x410.dev/) installed to allow graphical apps to show up on Windows.

Yeah, like I said, this is super niche.

Requirements
------------

There are no major requirements here.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

There are no major dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Patrick Wagstrom &lt;patrick@wagstrom.net&gt;

- https://patrick.wagstrom.net/
- https://github.com/pridkett/