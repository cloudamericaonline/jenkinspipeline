pipeline {
  agent none
  stages {
    stage('error') {
      steps {
        sh '''#!/bin/bash

echo "Hello From Jenkins"'''
      }
    }
  }
  environment {
    Dev = 'Dev1'
  }
}