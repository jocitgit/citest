pipeline {
  agent {
    docker {
      image 'maven:alpine'
      args '-v /root/.m2:/root/.m2'
    }
    
  }
  stages {
    stage('stage1') {
      steps {
        sh 'mvn --version'
        echo 'hello'
      }
    }
  }
}