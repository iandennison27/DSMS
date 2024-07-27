DSMS sudoers
===============

This is a management utility to build and distribute Sudoers files over large landscapes.

(c) Ian Dennison 2024

Overview
-------------
This utility provides a central point for creating the content for Sudoers files and distributing the resulting files to the client Servers.
It removes the need to edit the file directly, verifies the changes before distribution and audits the actions of those maintaning the system.

Features
-------------
* Individual signons for tracking User changes
* Supports AD groups usage for User specification
* Performs deploy to hosts only on change of content
* Supports RHEL, SunOS, and other Linux variants as clients
* Time expired access can be configured
* Cutdown sudoers files for public facing / DMZ Hosts
* Reverse engineering script for existing installations (prototype only)

Requirements
-------------
* RHEL 7 Host
* PHP / Apache
* mysql / mariadb

Upcoming Changes
----------------
System will be rewritten for RHEL 8+ sometime in 2024/5

