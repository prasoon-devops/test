pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "Build completed"
      }
    }
    stage('Test') {
      steps {
        echo "Test completed"
      }
    }
    stage('Deployment') {
      steps {
        echo "Deployment completed"
      }
    }
  }
  post {
    always { echo "do nothing" } // always or success or failure
  }
}
    
