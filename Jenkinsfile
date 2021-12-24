pipeline {
  agent {
    node {
      label 'WindowsLabel'
    }

  }
  stages {
    stage('Source') {
      steps {
        echo 'hello'
      }
    }

    stage('Python') {
      steps {
        bat 'python pyfile.py'
      }
    }

  }
}