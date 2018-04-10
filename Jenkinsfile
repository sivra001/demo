pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('maven') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}