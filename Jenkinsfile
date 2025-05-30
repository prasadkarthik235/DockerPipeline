pipeline {
  agent {
    docker { image 'alpine' }
    args '-u root'
  }
  stages {
    stage('Hello') {
      steps {
        sh 'echo Hello from Docker container!'
      }
    }
  }
}
