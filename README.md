# Ansible Role: `buildtools`

Install buildtools on your system.

      <!-- BADGE_PLACEHOLDER -->

## Example Playbook

This example is taken from [`molecule/default/converge.yml`](https://github.com/shaneholloman/ansible-role-buildtools/blob/main/molecule/default/converge.yml) and is tested on each push, pull request and release.

```yml
---
- name: Converge
  hosts: all
  become: yes
  gather_facts: yes

  roles:
    - role: shaneholloman.buildtools
```

The machine needs to be prepared. In CI this is done using [`molecule/default/prepare.yml`](https://github.com/shaneholloman/ansible-role-buildtools/blob/main/molecule/default/prepare.yml):

```yml
---
- name: Prepare
  hosts: all
  gather_facts: no
  become: yes

  roles:
    - role: shaneholloman.bootstrap
```

Also see a [full explanation and example](https://shaneholloman.com/how-to-use-these-roles.html) on how to use these roles.

## Requirements

- pip packages listed in [requirements.txt](https://github.com/shaneholloman/ansible-role-buildtools/blob/main/requirements.txt).

## Context

This role is a part of many compatible roles. Have a look at [the documentation of these roles](https://shaneholloman.com/) for further information.

Here is an overview of related roles:
![dependencies](https://raw.githubusercontent.com/shaneholloman/ansible-role-buildtools/png/requirements.png "Dependencies")

## Compatibility

This role has been tested on these [container images](https://hub.docker.com/u/shaneholloman):

The minimum version of Ansible required is 2.12, tests have been done to:

- The previous version.
- The current version.
- The development version.

If you find issues, please register them in [GitHub](https://github.com/shaneholloman/ansible-role-buildtools/issues)

## License

[Apache-2.0](https://github.com/shaneholloman/ansible-role-buildtools/blob/main/LICENSE).

## Author Information

[shaneholloman](https://shaneholloman.com/)
