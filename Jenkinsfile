pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
          echo 'Building...'
           ps -ef | grep java
           
          echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE_NAME} and JOB ${env.JOB_NAME}"
        }
   }
   stage('Test') {
     steps {
        echo 'Testing...'
        df -kh
     }
   }
   stage('Deploy') {
     steps {
       echo 'Deploying...'
        echo 'Lloyd is happy'
     }
   }
  }
}
