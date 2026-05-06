# GitLab CI

## Overview
GitLab CI uses a `.gitlab-ci.yml` file to define pipelines.

## Example
```yaml
stages:
  - build
build:
  stage: build
  script:
    - echo "Build"
```

## Interview questions with answers
- Q: What is a GitLab runner?
  A: The agent that executes GitLab CI jobs.
- Q: How do stages work?
  A: Jobs run by stage order, and later stages wait for earlier ones.
