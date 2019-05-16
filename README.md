# Ansible Role: apache_certificates

Create self signed virtual host certificate files defined for geerlingguy.apache role on Linux

## Requirements

    geerlingguy.apache

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    root_certificates_dir: "{{ playbook_dir }}/inventories/deploy/all/files/certs"

    Directory that contains self signed root CA certificate and key files
    named rootCA.crt and rootCA.key

## Dependencies

## Example Playbook

    - hosts: all
      roles:
        - Akman.apache_certificates

*Inside vars/main.yml*:

    root_certificates_dir: "{{ playbook_dir }}/inventories/deploy/all/files/certs"

## License

MIT / BSD

## Author Information

This role was created in 2018 by Alexander Kapitman
