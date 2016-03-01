vagrantbox-centos-basebox
=========

Builds a CentOS basebox image for use with vagrantbox

Requirements
------------

None. CentOS-7-x86_64-DVD-1511.iso will be downloaded to ~/vm/basebox/iso if it
does not already exist there.

Role Variables
--------------

defaults/main.yml
update_packages_first: True
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

vagrantbox-dev

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: vagrantbox-centos-basebox }

License
-------

To be determined

Author Information
------------------

None