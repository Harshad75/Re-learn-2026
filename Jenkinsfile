pipeline {
  agent { 
    label 'agent1' 
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "This is build number from Jenkinsfile: $BUILD_NUMBER and the job name is $JOB_NAME" > /tmp/$JOB_NAME_$BUILD_NUMBER.txt"
      }
    }
  }
}
