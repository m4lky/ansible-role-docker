# Docker Ansible Role

## Requirements

Ubuntu 20.04+ or 22.04+

## Example Playbook

```yaml
- hosts: docker_hosts
  become: true
  roles:
    - docker
