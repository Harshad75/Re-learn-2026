pipeline {
  agent { 
    label 'agentnew' 
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "This is build number from Jenkinsfile: $BUILD_NUMBER and the job name is $JOB_NAME" > /tmp/$JOB_NAME-$BUILD_NUMBER.txt'
      }
    }
  }
}
