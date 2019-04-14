# Ansible Role: guest_additions

[![Build Status](https://travis-ci.com/Bassinator/ansible-role-guest-additions.svg?branch=master)](https://travis-ci.com/Bassinator/ansible-role-guest-additions)

archives all updated files with a given fileextension to an archive folder

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    installation_os_user: vagrant
    installation_os_group: vagrant

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
