# Ansible Playbooks

## Overview
Playbooks define desired server state.

## Example
```yaml
- hosts: web
  tasks:
    - name: Install nginx
      apt:
        name: nginx
        state: present
```

## Interview questions with answers
- Q: What is a task in Ansible?
  A: A single action like installing a package.
- Q: What does idempotent mean in Ansible?
  A: Running it multiple times yields the same state.
