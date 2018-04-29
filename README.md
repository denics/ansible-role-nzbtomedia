nzbtomedia
==========

[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.nzbtomedia-green.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/nzbtomedia)

An Ansible role to install and configure nzbtomedia post processing scripts on Raspbian.

Requirements
------------

Overview
--------

List of tasks that will be performed under `nzbtomedia` role:

1. Get the latest nzbtomedia scripts for github
2. Configure postprocessing scripts in download clients (`denics.deluge` and `denics.sabnzbd` ) if installed.
3. Configure CouchPotato and Sickrage script integrations if installed ( `denics.couchpotato` and `denics.sickrage`)

`nzbtomedia` role will be installed as dependency for `denics.deluge` and `denics.sabnzbd`.