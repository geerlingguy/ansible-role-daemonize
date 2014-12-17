# Ansible Role: Daemonize

[![Build Status](https://travis-ci.org/geerlingguy/ansible-role-daemonize.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-daemonize)

Installs [Daemonize](http://software.clapper.org/daemonize/), a tool for running commands as a Unix daemon.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    TODO

## Dependencies

None

## Example Playbook

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - { role: geerlingguy.daemonize }

*Inside `vars/main.yml`*:

    TODO

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/).
