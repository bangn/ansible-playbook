Ansible Playbook to provision laptop.

## Prerequisite
[Ansible](https://www.ansible.com/) version >= 2.4

## Provision localhost

```bash
sh bootstrap.sh
```

## Run a tag

Example

```bash
ansible-playbook --ask-become-pass -i inventories/localhost playbook.yml --tag packages
```
