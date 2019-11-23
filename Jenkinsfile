pipeline {
  agent any
  stages {
    stage('Instanciando') {
      steps {
        echo 'Iniciando proceso'
        sh 'uname -a'
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