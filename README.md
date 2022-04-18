Ansible-7dtd-Server
=========

Ansible Role to install SteamCMD and download 7dtd server for Ubuntu Linux

Requirements
------------

None

Role Variables
--------------

my_password: your sudo password
my_pub_key: your public key
steam_password: steam user password
username: end user username

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - ansible-7dtd-server

License
-------

Creative Commons Attribution Non Commercial 4.0 International
