# GitHub Actions

## Overview
GitHub Actions runs workflows in your repo.

## Example
```yaml
name: CI
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - run: echo "Hello"
```

## Interview questions with answers
- Q: What is a workflow?
  A: A YAML file that defines CI jobs and steps.
- Q: What triggers a GitHub Actions workflow?
  A: Events like push, pull_request, or schedule.
