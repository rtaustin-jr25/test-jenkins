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
        sh 'mvn clean package -DskipTests'
      }
    }
    stage('Maven Deploy') {
      steps {
        sh 'mvn tomcat7:deploy'
      }
    }
  }
}