# Docker Manager

A role to initialise a new Docker Swarm Manager and store the swarm join tokens as host variables under a faux host called `swarm_tokens`.

## Example playbook

```yaml
- hosts: manager[0]
  roles:
    - manager
```
