Role Name
=========

Ansible role to install tomcat 10.1.1 on Debian, CentOS and Ubuntu

Tested on
------------

CentOS 7
CentOS Stream 8
CentOS Stream 9
Debian 10
Debian 11
Ubuntu 18.04
Ubuntu 20.04
Ubuntu 22.04

Installation
------------

ansible-galaxy install vikas-malik.tomcat10-multios

Role Variables
--------------

galaxy_info:
  author: vikas-malik
  role_name: tomcat
  description: "tomcat for Multiple Linux OS"
  company: "iSatOm technologies"
  license: "license (BSD, MIT)"

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

- name: Deploy Apache Tomcat10
  hosts: all
  gather_facts: true
  become: true
  roles:
    - tomcat

License
-------

BSD