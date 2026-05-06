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

## Interview questions
- What is a GitLab runner?
- How do stages work?
