pipeline {
  agent {
    docker {
      image 'sebp/elk'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        dockerNode(image: 'sebp/elk')
      }
    }
  }
}