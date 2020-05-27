pipeline {
  agent any
  stages {
    stage('Linter') {
      steps {
        sh 'tidy -q -e *.html'
      }
    }
    stage('Upload to AWS') {
      steps {
        withAWS(region:'us-east-2', credentials: 'aws-static') {
            s3Upload(file:'index.html', bucket:'udacityprojectjenkins', path:'index.html')
        }
      }
    }

  }
}
