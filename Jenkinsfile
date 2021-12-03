pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Any Message I want'
        echo 'Any Message I Want'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Foux Test'
          }
        }

        stage('') {
          steps {
            echo 'Secondary test'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'fake deployment of fake tests'
      }
    }

  }
}