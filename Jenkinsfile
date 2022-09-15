
pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
        withmMaven(maven : 'maven3'){
        sh 'mvn clean install'
   }
      }
    }

  }
}
