DSMS sudoers
===============

This is a management utility to build and distribute Sudoers files over large landscapes.

(c) Ian Dennison 2024

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>. 
    
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

