ansible-role-jackett
=========

An Ansible role to install Jackett on CentOS 7

Requirements
------------

CentOS/Red Hat Enterprise Linux 7

Role Variables
--------------

Defaults:

jackett_directory = /opt/jackett/ - directory to install jackett
jackett_user = jackett - user that will run jackett
jackett_home = /home/jackett- jackett_user home folder - jackett stores configs here
Vars:

jackett_prereqs - all jackett prerequisite packages that need to be installed via Yum
mono_baseurl - mono repo url
mono_gpgurl - mono repo gpgkey url

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: yes
      roles:
         - { role: mujahidhemani.jackett }

License
-------

GPLv3

Author Information
------------------

Author: Mujahid Hemani
