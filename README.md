# Ansible Role: certificates

Upload virtual host certificate files defined for geerlingguy.apache role on Linux

## Requirements

    geerlingguy.apache

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    apache_certificates_dir: "{{ playbook_dir }}"
    
    Directory that contains certificate files named as in vhost definition
    for geerlingguy.apache role

## Dependencies

## Example Playbook

    - hosts: all
      roles:
        - Akman.certificates

*Inside vars/main.yml*:

    apache_certificates_dir: "{{ playbook_dir }}/inventories/certificates"

## License

MIT / BSD

## Author Information

This role was created in 2018 by Alexander Kapitman
