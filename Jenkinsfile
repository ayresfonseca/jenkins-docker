pipeline {
  agent {
    docker {
      image 'hello-world'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'docker --version'
      }
    }

  }
}