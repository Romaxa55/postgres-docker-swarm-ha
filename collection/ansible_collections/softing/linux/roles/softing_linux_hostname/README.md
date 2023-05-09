# Sofing • Ansible • Linux

**Different Ansible roles for atomic Linux server configuration.**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_linux_hostname

This role sets a permanent hostname to linux server

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_linux_hostname
  vars:
    linux_hostname_hostname: "{{ hostname }}"
```

## License

[GNU GPLv3](../../LICENSE)

------------------------
[Back to index](../../)
