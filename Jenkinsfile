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
  }
}