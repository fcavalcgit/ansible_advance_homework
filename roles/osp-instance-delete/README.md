osp-instance-delete 
===================

This role is used to delete the servers instances from OpenStack.

Requirements
------------

It requires that the OSP environment is running and deployed. If no instances are found, nothing is done.

Role Variables
--------------

{{result.ansible_facts.openstack_servers}} : This is the list that contains the openstack servers. It is returned by the os_server_facts module.

