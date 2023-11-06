# Ansible Role: `terraform`

An Ansible Role that installs [`terraform`](https://github.com/hashicorp/terraform).

## Requirements

`unzip` must be installed on the target host.

## Role Variables

Available variables are in [`defaults/main.yml`](defaults/main.yml)

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - m18uet.terraform
```

## License

[MIT](LICENSE)

## Author Information

This role was created in 2017 by [Muhammed Kahrimanoglu](https://www.m18u.net)
