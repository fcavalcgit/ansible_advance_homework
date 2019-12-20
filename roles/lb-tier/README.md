lb-tier
=========

This role installs haproxy, enables it, makes its initial configuration and restarts it.

Requirements
------------

It needs to have the haproxy.cfg.j2 placed in the templates directory so it can create the haproxy.cfg file.

Role Variables
--------------

payload:          haproxy  				#### used to install the service for haproxy

