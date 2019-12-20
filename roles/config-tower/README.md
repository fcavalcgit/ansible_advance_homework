config-tower
============

This role includes tasks to install and configure the OSP workstation as an isolated node. The tasks are:
- pre-config-tower.yml
- post-config-tower.yml
- ec2_dynamic.yml
- job_template.yml
- workflow_template.yml

Requirements
------------

The Tower and OSP labs must be running. The OpenTLC user and password is required for creating the 3-tier lab. The openstack.pem and mykey.pem must be correctly setup and available in the ~/.ssh directory

Role Variables
--------------

There are several variables being used by this role that are setup in the 'roles/config-tower/vars/main.yml'. Refer to this file to review all the variables.
