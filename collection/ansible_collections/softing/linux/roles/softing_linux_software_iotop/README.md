# Sofing • Ansible • Linux

**Different Ansible roles for atomic Linux server configuration.**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_linux_software_iotop

This role installs the iotop package - simple top-like I/O monitor

https://manpages.ubuntu.com/manpages/focal/en/man8/iotop.8.html

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_linux_software_iotop
```

## License

[GNU GPLv3](../../LICENSE)

------------------------
[Back to index](../../)
