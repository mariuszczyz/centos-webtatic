## CentOS 7 Webtatic Repository Installation Role

## Requirements

None.

## Role Variables

## Dependencies

None.

## Example Playbook

Fetch this role from Ansible Galaxy:

`ansible-galaxy install mariuszczyz.centos-webtatic`

In playbook.yml:

```yaml
- hosts: servers
  roles:
    - { role: mariuszczyz.centos-webtatic, tags: ['webtatic'] }
```

Run it:

`ansible-playbook -i hosts playbook.yml --user root --ask-pass --limit=servers`

## License

BSD

## Author Information

Author: Mariusz Czyz
Date: 10/2018
