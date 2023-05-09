# Sofing • Ansible • Linux

**Different Ansible roles for atomic Linux server configuration.**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_linux_software_postfix

This role installs the postfix package - Postfix mail relay

https://manpages.ubuntu.com/manpages/focal/en/man1/postfix.1.html

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_linux_software_postfix
  vars:
    linux_software_postfix_default_email: 'user@mail.com'
    linux_software_postfix_relay_user: 'user'
    linux_software_postfix_relay_password: 'password'
    linux_software_postfix_relay_server: 'smtp.mailgun.org'
    linux_software_postfix_relay_sever_port: '2525'
```

## License

[GNU GPLv3](../../LICENSE)

------------------------
[Back to index](../../)
