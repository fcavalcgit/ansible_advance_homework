osp-facts
=========

This role gathers information about the OSP environment and then it adds the hosts and groups to the ansible-playbook in-memory inventory

Requirements
------------

It requires that the OSP environment is running and deployed.

Role Variables
--------------

{{result.ansible_facts.openstack_servers}} : This is the list that contains the openstack servers. It is returned by the os_server_facts module.
