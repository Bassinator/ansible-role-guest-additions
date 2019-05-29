# Ansible Role: guest_additions

[![Build Status](https://travis-ci.com/Bassinator/ansible-role-guest-additions.svg?branch=master)](https://travis-ci.com/Bassinator/ansible-role-guest-additions)

Installs virtualbox guest additions matching virtualbox version.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    installation_os_user: vagrant

## Dependencies

None.


## Example Playbook


    - hosts: all
      roles:
         - role: bassinator.guest_additions

## License

GNU GPLv3

## Author Information
This role was created in 2018 by [Bastian Bukatz](https://bassinator.github.io).
