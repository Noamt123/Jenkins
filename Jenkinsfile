pipeline {
  agent any
  stages {
    stage('poop') {
      steps {
        echo 'hi'
      }
    }
    stage('s3') {
      steps {
        s3Upload(bucket: 'poopy-crap', pathStyleAccessEnabled: true, payloadSigningEnabled: true, file: 'index.html')
      }
    }
  }
}