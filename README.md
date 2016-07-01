# Mezuro Playbooks

Ansible playbooks for setting up the mezuro.org services

## Requirements

* Ansible
* 3x Ubuntu 16.04 machines acessible through ssh

## Usage

`ansible all -m ping -u <USERNAME>`

## Development

The environment is based on Docker within Vagrant.

`vagrant up --provider docker`

## License

This is licensed under GPLv3 (see COPYING file) by the AUTHORS (see AUTHORS file).