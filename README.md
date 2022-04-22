# [package_cache](#package_cache)

Update package cache for systems package manager module.

|GitHub|Version|Ansible Galaxy|Quality|Downloads|
|------|-------|--------------|-------|---------|
|[![github](https://github.com/ucomesdag/ansible-role-package_cache/workflows/Ansible%20Molecule/badge.svg)](https://github.com/ucomesdag/ansible-role-package_cache/actions)|[![version](https://img.shields.io/github/v/release/ucomesdag/ansible-role-package_cache)](https://github.com/ucomesdag/ansible-role-package_cache/releases/)|[![role](https://img.shields.io/ansible/role/58885)](https://galaxy.ansible.com/ucomesdag/package_cache)|[![quality](https://img.shields.io/ansible/quality/58885)](https://galaxy.ansible.com/ucomesdag/package_cache)|[![downloads](https://img.shields.io/ansible/role/d/58885)](https://galaxy.ansible.com/ucomesdag/package_cache)|

## [Example Playbook](#example-playbook)

This example is taken from `molecule/resources/converge.yml` and is tested on each push, pull request and release.
```yaml
---
- name: Converge
  hosts: all
  become: yes
  gather_facts: no

  roles:
    - role: ucomesdag.package_cache
```

## [Role Variables](#role-variables)

These variables are set in `defaults/main.yml`:
```yaml
---
# defaults file for package_cache


```

## [Dependencies](#dependencies)

Overview of role dependencies:

![dependencies](https://raw.githubusercontent.com/ucomesdag/ansible-role-package_cache/png/requirements.png "Dependencies")

## [Requirements](#role-requirements)

- pip packages listed in [requirements.txt](https://github.com/ucomesdag/ansible-role-package_cache/blob/master/requirements.txt).

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://quay.io/user/ucomesdag):

|container      |tags                     |
|---------------|-------------------------|
|alpine         |edge, latest             |
|amazonlinux    |latest                   |
|archlinux      |latest                   |
|centos         |latest, stream8          |
|debian         |latest, buster           |
|fedora         |rawhide, latest, 34, 33  |
|opensus        |latest                   |
|rhel           |latest                   |
|rocky          |latest                   |
|rpi-os         |latest                   |
|ubuntu         |jammy, latest, bionic    |

The minimum version of Ansible required is 2.10, tests have been done to:

- The previous version.
- The current version.
- The development version.

See the [Ansible community changelogs](https://docs.ansible.com/ansible/devel/reference_appendices/release_and_maintenance.html#ansible-community-changelogs) for details.

## [Exceptions](#exceptions)

Some variarations of the build matrix do not work. These are the variations and reasons why the build won't work:

| variation   | reason                                |
|-------------|---------------------------------------|
|             |                                       |


If you find issues, please register them in [GitHub](https://github.com/ucomesdag/ansible-role-package_cache/issues)

## [License](#license)

Apache-2.0
