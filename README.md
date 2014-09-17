## phpredis [![Build Status](https://travis-ci.org/Oefenweb/ansible-phpredis.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-phpredis)

Set up PhpRedis in Debian-like systems.

#### Requirements

* `php5-dev` (will be installed)
* `build-essential` (will be installed)
* `git` (will be installed)

#### Variables

* `phpredis_version` [default: `2.2.5`]: What version of phpredis to check out (set up). This can be the full 40-character SHA-1 hash, the literal string HEAD, a branch name, or a tag name 

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
  - phpredis
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-phpredis/issues)!
