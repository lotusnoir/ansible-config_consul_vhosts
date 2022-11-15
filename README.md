# ansible-config_consul_vhosts

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-config_consul_vhosts-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/config_consul_vhosts)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-config_consul_vhosts.svg)](https://github.com/lotusnoir/ansible-config_consul_vhosts/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-config_consul_vhosts?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/config_consul_vhosts)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/config_consul_vhosts)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/config_consul_vhosts)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Create consul catalog vhosts in order to see them in traefik

## Requirements

- lotusnoir.apps_consul_agent


## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: config_consul_vhosts
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-config_consul_vhosts


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

