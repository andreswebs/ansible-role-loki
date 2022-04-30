# ansible-role-loki

Ansible role to install loki.

## Requirements

The `jq` program must be installed on the host. See the
[jq web page](https://stedolan.github.io/jq/) to install.

## Install

```sh
ansible-galaxy install andreswebs.loki
```

## Example Playbook

```yaml
---
- hosts: servers
  roles:
    - role: andreswebs.loki
```

## Authors

**Andre Silva** [@andreswebs](https://github.com/andreswebs)

## License

This project is licensed under the [Unlicense](UNLICENSE.md).
