# Ansible Role: Ambari Agent

Installs the Ambari Agent for RHEL/CentOS.

## Requirements

This role only is needed/runs on RHEL and its derivatives.

## Role Variables

None.

## Dependencies

Depends on Ambari Repo

## Example Playbook

    - hosts: servers
      roles:
        - { role: ambari-agent }

## License

MIT / BSD

## Author Information

This role was created by Sean Roberts.
This role was enhanced by Ming Zhang.
