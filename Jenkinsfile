pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'echo "Hello world!"'
      }
    }

    stage('npmstart') {
      steps {
        bat 'npm start'
      }
    }

  }
}