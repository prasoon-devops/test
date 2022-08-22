pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "Build completed"
      }
    }
    stage('Test') {
      when {
        expression {
         BRANCH_NAME == 'dev' 
        }
      }
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
    always { 
      echo "do nothing" 
    } 
    // always or success or failure
  }
}
    
