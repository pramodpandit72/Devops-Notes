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

## Interview questions with answers
- Q: What is a Jenkinsfile?
  A: A file that defines a pipeline as code.
- Q: What is the difference between scripted and declarative pipeline?
  A: Declarative is structured and simpler; scripted is more flexible.
