# Sofing • Ansible • Linux

**Different Ansible roles for atomic Linux server configuration.**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_linux_software_apt

This role installs additional packages for apt to work correctly:

- apt-transport-https
- ca-certificates
- software-properties-common

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_linux_software_apt
```

## License

[GNU GPLv3](../../LICENSE)

------------------------
[Back to index](../../)
