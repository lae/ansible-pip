# lae.pip

An Ansible role for installing [pip](https://pip.pypa.io/en/latest/).

## Role Variables

- `pip_version` - pip version
- `pip_src_path` - location to drop `get-pip.py` into

## Example Playbook

```
- hosts: all
  become: True
  roles:
    - lae.pip
```
