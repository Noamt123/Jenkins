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
        s3Upload(bucket: 'poopy-crap', includePathPattern: 'poopy-crap/', path: 'poopy-crap/', workingDir: '/poopy-crap/')
      }
    }
  }
}