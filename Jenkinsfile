pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Tarefas para construir, instalar,...'
      }
    }
    stage('Comprobación inicial') {
      steps {
        sh "ls"
      }
    }
    stage('Test') {
      steps {
        echo 'Tarefas para realizar test.'
      }  
    }
    stage('Deploy') {
      steps {
        echo 'Tarefas para desplegar, construir, ...'
      }
    }
  }
}
