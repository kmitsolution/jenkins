pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build is done'
          }
        }

        stage('Sidebar') {
          steps {
            echo 'paraellel build'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Testing'
      }
    }

  }
}