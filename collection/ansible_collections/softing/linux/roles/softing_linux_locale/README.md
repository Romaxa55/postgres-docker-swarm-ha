# Sofing • Ansible • Linux

**Different Ansible roles for atomic Linux server configuration.**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_linux_locale

This role adds locales to Linux. Default locale is `en_US.UTF-8`. All others are added to the default locale.

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_linux_locale
  vars:
    linux_locale_locales:
      - ru_RU.UTF-8
```

## License

[GNU GPLv3](../../LICENSE)

------------------------
[Back to index](../../)
