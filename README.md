# Ansible role for installing nginx with self-signed certificate

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    domain: []

## Usage example

```yml
- name: install nginx
    hosts: localhost
    connection: local
    become: yes
    vars:
      - domain: example.com
    roles:
    - ansible_innovation_nginx
```

## License

MIT License

## Author

<http://github.com/RenderQwerty/>
