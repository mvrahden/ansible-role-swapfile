# ansible-role-ssh <!-- omit in toc -->

An [Ansible](https://www.ansible.com) role to favor dynamic swapfiles over static swap devices on debian based systems.

## Table of Contents <!-- omit in toc -->

- [Side notes](#Side-notes)
- [Role Variables](#Role-Variables)
- [Dependencies](#Dependencies)
  - [Requirements](#Requirements)
- [License](#License)
- [Author Information](#Author-Information)

## Side notes

- By default swapfile service is enabled as a result of this role. To switch it off, please set default variable `swapfile_swapon` to false.

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

### Requirements

Packages installed on your system:

- [Ansible](https://www.ansible.com)

## License

MIT

## Author Information

- Menno van Rahden
