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
            echo 'Secondary test worked and I am able to write this message and my fake pipleline is ready to deploy'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'fake deployment of fake tests except i dont know what Im doing'
      }
    }

  }
}
