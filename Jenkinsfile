pipeline {
  agent any
  stages {
    stage('first') {
      steps {
        sh 'echo Stage 1'
      }
    }

    stage('error') {
      steps {
        sh 'echo Stage 2'
      }
    }

  }
  environment {
    ECS_CLUSTER = 'jenkins-pipeline-demo'
  }
}