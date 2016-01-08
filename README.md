Ansible Role: thomo.inadyn [![Build Status](https://travis-ci.org/thomo/ansible-inadyn.svg?branch=master)](https://travis-ci.org/thomo/ansible-inadyn)
=========

Ansible role to install and configure inadyn-mt.

I use it by myself on CentOS 7.

Installation
------------
### Ansible Galaxy

If you want to install it in the local ansible project dir:

    ansible-galaxy install -p roles thomo.inadyn

To install it on system level

    ansible-galaxy install thomo.inadyn

### Manual

Alternative you can install it by downloading it from github.

    wget https://github.com/thomo/ansible-inadyn/archive/master.zip
    unzip -d roles master.zip
    mv roles/ansible-inadyn-master roles/thomo.inadyn


Role Variables
--------------



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: thomo.inadyn

 License
 -------

 **MIT** - see LICENSE file for details.

 Author Information
 ------------------

 Thomas Mohaupt https://github.com/thomo/ansible-inadyn
