os_update
=========

This role will update the packages of an RedHat or Ubuntu linux distribution and reboot the server if needed

Requirements
------------

Ansible 2.4 required

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Here an example of a Playbook:

    - hosts: servers
      become: true
      
      roles:
         - role: Synehan.os_update

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
