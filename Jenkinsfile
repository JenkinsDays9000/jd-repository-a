library 'SharedLibs'

pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('First Stage') {
      steps {
        sh 'mvn -v'
      }
    }
    stage('Shared Lib') {
       steps {
           helloWorld("Jenkins")
       }
    }
  }
}
