# Ansible Role: Plex
[![Gitlab pipeline status (self-hosted)](https://git.dubzland.net/dubzland/ansible-role-plex/badges/master/pipeline.svg)](https://git.dubzland.net/dubzland/ansible-role-plex)

Installs and configures the Plex Media Server.

## Requirements

Ansible version 2.0 or higher.

## Role Variables

None

## Dependencies

None

## Example Playbook

```yaml
- hosts: plex-servers
  become: yes
  roles:
  - role: dubzland.plex
```

## License

MIT

## Author

* [Josh Williams](https://codingprime.com)
