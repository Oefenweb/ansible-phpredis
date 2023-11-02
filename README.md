## phpredis

[![CI](https://github.com/Oefenweb/ansible-phpredis/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-phpredis/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-phpredis-blue.svg)](https://galaxy.ansible.com/Oefenweb/phpredis)

Set up [PhpRedis](https://github.com/phpredis/phpredis) in Debian-like systems.

#### Requirements

* `php5-dev` (will be installed)
* `build-essential` (will be installed)
* `git` (will be installed)

#### Variables

* `phpredis_version` [default: `2.2.7`]: What version of phpredis to check out (set up). This can be the full 40-character SHA-1 hash, the literal string HEAD, a branch name, or a tag name

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.phpredis
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-phpredis/issues)!
