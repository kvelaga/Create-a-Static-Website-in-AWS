pipeline {
  agent any
  stages {
    stage('Upload to AWS') {
      steps {
        withAWS(region:'eu-east-2', credentials: 'aws-static') {
            s3Upload(file:'index.html', bucket:'udacityprojectjenkins', path:'index.html')
        }
      }
    }

  }
}
