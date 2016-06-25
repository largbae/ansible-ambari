# Ansible Role: Ambari Server

Installs the Ambari Server for RHEL/CentOS.

## Requirements

This role only is needed/runs on RHEL and its derivatives.

## Role Variables

None.

## Dependencies

Depends on Ambari Repo

## Example Playbook

    - hosts: servers
      roles:
        - { role: ambari-server }

## License

MIT / BSD

## Author Information

This role was created by Sean Roberts.
This role was enhanced by Ming Zhang.
