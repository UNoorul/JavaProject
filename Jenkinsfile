pipeline {
  agent any
  stages {
    stage('Compile Stage') {
      parallel {
        stage('Compile Stage') {
          steps {
            echo ' Welcome to Compile Stage'
            sleep 3
          }
        }

        stage('MyBlue') {
          steps {
            echo 'Compile New stage'
            git(url: 'https://github.com/UNoorul/JavaProject', branch: 'master ')
          }
        }

      }
    }

    stage('Testing Stage') {
      steps {
        echo 'Testing '
        sleep 3
      }
    }

    stage('Deployment Stage') {
      steps {
        echo 'Deployment'
        sleep 3
      }
    }

  }
}