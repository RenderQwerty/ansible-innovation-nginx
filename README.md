# Ansible role for installing nginx with self-signed certificate

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    domain: []

## Usage example

```yml
- hosts: localhost
  connection: local
  become: yes
  vars:
    - domain: example.com
  roles:
    - renderqwerty.ansible_innovation_nginx
```

## License

MIT License

## Author

<http://github.com/RenderQwerty/>
