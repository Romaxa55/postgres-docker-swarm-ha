# Sofing • Ansible • Linux

**Different Ansible roles for atomic Linux server configuration.**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_linux_timezone

This role installs the `tzdata` package and sets the necessary timezone

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_linux_timezone
  vars:
    linux_timezone_timezone: Europe/Berlin
```

## License

[GNU GPLv3](../../LICENSE)

------------------------
[Back to index](../../)
