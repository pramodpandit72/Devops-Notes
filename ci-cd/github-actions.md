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

## Interview questions
- What is a workflow?
- What triggers a GitHub Actions workflow?
