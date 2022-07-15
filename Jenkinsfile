pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'build is sucessfull'
          }
        }

        stage('test') {
          steps {
            echo 'test sucessful'
          }
        }

        stage('deploy') {
          steps {
            echo 'deployed to server'
          }
        }

      }
    }

  }
}