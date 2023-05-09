# Sofing • Ansible • Linux

**Different Ansible roles for atomic Linux server configuration.**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_linux_software_ping

This role installs the ping package - send ICMP ECHO_REQUEST packets to network hosts

https://manpages.ubuntu.com/manpages/focal/en/man1/ping.1.html

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_linux_software_ping
```

## License

[GNU GPLv3](../../LICENSE)

------------------------
[Back to index](../../)
