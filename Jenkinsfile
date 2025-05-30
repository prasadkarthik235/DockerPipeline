pipeline {
  agent {
    docker { image 'alpine'
             args '--workdir /home/jenkins'
           }
    
  }
  stages {
    stage('Hello') {
      steps {
        sh 'echo Hello from Docker container!'
      }
    }
  }
}
