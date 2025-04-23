Role Name
=========

Openvpn server configuration role, handles everything, just run the .ovpn file (Will apear in the directory where the playbook is ran)

Requirements
------------

Remote Ubuntu machine

Role Variables
--------------

server_ip - No need to configure, being set automatically to the remote ansible host

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - openvpn

License
-------

BSD

Author Information
------------------

Dor Attar
dorattar4@gmail.com
https://github.com/shmador
