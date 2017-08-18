pipeline {
  agent {
    docker {
      image 'sebp/elk'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        cloudshareDockerMachine()
      }
    }
  }
}