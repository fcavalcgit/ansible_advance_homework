osp-servers
===========

This role creates new OSP servers instances, attaches them a network and passes metadata to the instance. Then it adds floating IP to the servers and waits for the servers to become available.

Requirements
------------

OSP lab must be up. 

Role Variables
--------------

Variables to define the 3-tier-app instances ( defined in roles/osp-servers/vars/main.yml):
osp_servers:
  frontend
  app1
  app2
  db
