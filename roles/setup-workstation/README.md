setup-workstation
=================

This role is a collection of tasks to setup the OSP workstation. The task include:
- Pre-tasks, to install openstacksdk library, setup ospcloud and setup osp ssh keys
- Create Flavor: to add the osp flavor that will be used
- Create Keypair: to generate and add a keypair from OpenStack
- Create Security Groups: to add the security groups from OpenStack that will be used by the 3-tier-app deployment
- Create Image: to download and create an RHEL OpenStack image
- Create Network: to create the OpenStack network according to the requirements

Requirements
------------

OpenStack lab must be up.

Role Variables
--------------

osp_networks: contains the Public and Private facing networks configuration
osp_router: contains the configuration for the OSP router
