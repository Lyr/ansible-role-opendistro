Open Distro roles collections
=========

This collections aims to provide a necessary roles to deploy a fully complete open distro task (elasticsearch/kibana and other settings plugins like security, perf, ldap etc...).

Requirements
------------

The hosts targetd must have a way to download opendistro and elasticsearch packages. It could be with packages system like yum, apt or by http/package server like nexus or other solution which expose an http url this mandatory packages.
For offline or firewalled hosts, a totall switch is possible.

Roles
------------

A list of roles provided by this collections ( available on the roles directory with specific README file for more details):
* opendistro_elasticsearch : to install from scrath a new fresh elasticsearch cluster (with n nodes) 
*

License
-------

BSD

Author Information
------------------

Author is (Lyr)[https://github.com/Lyr].
