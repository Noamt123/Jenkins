pipeline {
  agent any
  stages {
    stage('poop') {
      steps {
        echo 'hi'
      }
    }
    stage('oof') {
      steps {
        s3Upload(bucket: 'poopy-crap', text: 'why', verbose: true, path: 'poopy-crap/', pathStyleAccessEnabled: true, payloadSigningEnabled: true, workingDir: '/poopy-crap/', file: 'index.html')
      }
    }
  }
}