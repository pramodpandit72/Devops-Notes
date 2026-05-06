# Jenkins Pipeline

## Overview
Pipeline is Jenkins as code using a Jenkinsfile.

## Example
```groovy
pipeline {
  agent any
  stages {
    stage('Build') { steps { sh 'mvn package' } }
  }
}
```

## Interview questions
- What is a Jenkinsfile?
- What is the difference between scripted and declarative pipeline?
