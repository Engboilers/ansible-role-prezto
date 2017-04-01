# Ansible Role: Prezto

[![Build Status](https://travis-ci.org/engboilers/ansible-role-prezto.svg?branch=master)](https://travis-ci.org/engboilers/ansible-role-prezto)

Installs prezto and the powerlevel9k theme.

## Requirements

None.

## Role Variables

None.

## Dependencies

  - [Engboilers.zsh](https://galaxy.ansible.com/engboilers/zsh/)

## Example Playbook

    - hosts: localhost
      roles:
        - { role: Engboilers.prezto, prezto_execute: true }

## License

Apache 2.0
