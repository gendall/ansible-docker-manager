# Docker Manager

A role to initialise a new Docker Swarm Manager and store the swarm join tokens as host variables under a fake host called `swarm_tokens`.

## Usage

Include this role in a playbook using a [requirements.txt](https://galaxy.ansible.com/docs/using/installing.html#installing-multiple-roles-from-a-file) file.

### Example playbook

```yaml
- hosts: manager[0]
  roles:
    - manager
```

## Deployment

This role will be automatically built and deployed to [Ansible Galaxy](https://galaxy.ansible.com/gendall) when a [Semver](https://semver.org) tag is pushed to the repo.
