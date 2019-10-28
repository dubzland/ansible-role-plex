# Dubzland: Plex
![Gitlab pipeline status (self-hosted)](https://img.shields.io/gitlab/pipeline/jdubz/dubzland-plex?gitlab_url=https%3A%2F%2Fgit.dubzland.net)

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
  - role: dubzland-plex
```

## License

MIT

## Author

* [Josh Williams](https://codingprime.com)
