pipeline {
  agent any
  stages {
    stage('ll') {
      parallel {
        stage('hehe') {
          steps {
            sh 'echo "${name}"'
          }
        }
        stage('lla') {
          steps {
            echo 'nima'
          }
        }
      }
    }
  }
  environment {
    name = 'linyao'
    age = '24'
  }
}