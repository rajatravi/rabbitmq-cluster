# Ansible Role: RabbitMQ

Installs RabbitMQ on Linux.

## Requirements

(Red Hat / CentOS only) Requires the EPEL repository, which can be installed with the `geerlingguy.repo-epel` role.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    
TODO

TODO.

## Dependencies

None.

## Example Playbook

    - hosts: rabbitmq
      roles:
        - name: geerlingguy.repo-epel
          when: ansible_os_family == 'RedHat'
        - geerlingguy.rabbitmq

## License



## Author Information

This role was created in 2018 by [Rajat Ravi]
