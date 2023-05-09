# Sofing • Ansible • Linux

**Different Ansible roles for atomic Linux server configuration.**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_linux_software_unzip

This role installs the unzip package - list, test and extract compressed files in a ZIP archive

https://manpages.ubuntu.com/manpages/focal/man1/unzip.1.html

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_linux_software_unzip
```

## License

[GNU GPLv3](../../LICENSE)

------------------------
[Back to index](../../)
