pipeline {
  agent any
  stages {
    stage('Upload to AWS') {
      withAWS(region:'eu-east-2', credentials: 'AKIAWVKXBV2SH6BHT37N') {
          s3Upload(file:'index.html', bucket:'udacityprojectjenkins', path:'index.html')
      }
    }

  }
}
