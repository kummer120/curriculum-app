pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/kummer120/curriculum-app', branch: 'dev')
      }
    }

    stage('ls -a') {
      steps {
        sh 'ls -la'
      }
    }

  }
}