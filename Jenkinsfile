pipeline {
  agent {
    label "jenkins-go"
  }
  environment {
    ORG = 'upendrasahu'
    APP_NAME = 'pipeline2'
  }
  stages {
    stage('Stage 1') {
      steps {
        sh "echo testpipeline"
      }
    }
    stage('Stage 2') {
      steps {
        sh 'echo testpipeline'
      }
    }
  }
}