# Sofing • Ansible • Linux

**Different Ansible roles for atomic Linux server configuration.**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_linux_hosts

This role adds entries to the /etc/hosts file

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_linux_hosts
  vars:
    linux_hosts_hosts:
      - address: "127.0.0.1"
        hostnames: "hostname_alias"
```
   

## License

[GNU GPLv3](../../LICENSE)

------------------------
[Back to index](../../)
