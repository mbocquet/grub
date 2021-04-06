# GRUB

Ansible role to configure grub.

## Requirements

None.

## Role Variables

See defaults/main.yml for details

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://git.sekoya.org/mb/grub.git roles/grub`

## Example Playbook

    - hosts: servers
      roles:
         - grub


    - hosts: servers
      roles:
         - { role: grub, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
