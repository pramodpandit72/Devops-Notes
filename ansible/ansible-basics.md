# Ansible Basics

## Overview
Ansible automates server setup using playbooks.

## Key ideas
- Agentless (uses SSH)
- YAML-based playbooks

## Important commands
- `ansible --version` use: show Ansible version
- `ansible all -m ping -i hosts` use: test connectivity

## Interview questions with answers
- Q: What is inventory?
	A: A list of target hosts and groups.
- Q: Why is Ansible agentless?
	A: It uses SSH and does not require a client agent.
