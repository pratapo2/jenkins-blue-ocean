pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'hi how are you test is completed'
      }
    }

    stage('build') {
      steps {
        sh 'w'
      }
    }

    stage('deploy-on-test') {
      steps {
        echo 'deployed on '
        echo 'deployed on testing machine'
      }
    }

    stage('deployed-on-prod') {
      steps {
        echo 'deployed on prod'
      }
    }

  }
}