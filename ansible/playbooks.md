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

## Interview questions
- What is a task in Ansible?
- What does idempotent mean in Ansible?
