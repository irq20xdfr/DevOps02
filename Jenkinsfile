pipeline {
  agent any
  stages {
    stage('Instanciando') {
      steps {
        echo 'Iniciando proceso'
        sh '''uname -a
php -v'''
      }
    }

    stage('Compila') {
      steps {
        sh 'gcc main.c -o main'
      }
    }

    stage('Correr') {
      steps {
        sh './main'
      }
    }

  }
}