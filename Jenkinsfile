pipeline {
  agent any
  stages {
    stage('Nonsense') {
      steps {
        echo 'Guess What!'
      }
    }
    stage('Maven Build') {
      steps {
        sh 'mvn clean package -BskipTests'
      }
    }
  }
}