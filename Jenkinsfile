pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        echo 'Gitting...'
      }
    }
    stage('Build') {
      steps {
        echo 'Building...'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing...'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying...'
      }
    }
    stage('Notify') {
      steps {
        echo 'Notifying...'
        mail bcc: '', body: 'THIS IS A TEST', cc: '', from: '', replyTo: '', subject: 'This is a test', to: 'serpentkekole@gmail.com'
      }
    }
  }
}
