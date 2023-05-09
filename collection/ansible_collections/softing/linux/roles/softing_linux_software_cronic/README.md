# Sofing • Ansible • Linux

**Different Ansible roles for atomic Linux server configuration.**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_linux_software_cronic

This role installs the cronic package - a shell script to help control the most annoying feature of cron: unwanted emailed output

https://manpages.ubuntu.com/manpages/jammy/man1/cronic.1.html

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_linux_software_cronic
```

## License

[GNU GPLv3](../../LICENSE)

------------------------
[Back to index](../../)
