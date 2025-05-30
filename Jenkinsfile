pipeline {
  agent {
    docker { image 'alpine' }
    }
  stages {
    stage('Hello') {
      steps {
        bat 'echo Hello from Docker container!'
      }
    }
  }
}
