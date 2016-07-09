# Ansible Role: M/Monit

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-mmonit.svg)](https://travis-ci.org/tschifftner/ansible-role-mmonit)

Installs M/Monit on Debian/Ubuntu linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    mmonit_workspace: '/opt'

## Dependencies

None.

## Example Playbook

    - hosts: server
      roles:
        - { role: tschifftner.mmonit }

## Login

| Url | Username | Password |
|--- |--- |--- |
| http://www.example.org:2811 | admin | swordfish |

Please change the credentials within your project!

## License

MIT / BSD

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)