pipeline {
  agent {
    docker { image 'alpine' 
            args '-u root'
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
