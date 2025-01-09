pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
ls'''
      }
    }

    stage('test') {
      steps {
        echo 'test is pass'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}