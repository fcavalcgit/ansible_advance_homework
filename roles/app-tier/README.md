app-tier
=========

This role installs tomcat, enables it, makes its initial configuration and restarts it.

Requirements
------------

It needs to have the index.html.j2 placed in the templates directory so it can create the index.html file.

Role Variables
--------------

payload:          tomcat  				#### used to install the service for tomcat
tomcat_web_root:  /usr/share/tomcat/webapps/ROOT	#### the root directory for tomcat

