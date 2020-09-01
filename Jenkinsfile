pipeline {
  agent any
  stages {
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
    }
    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }
    stage('Send Email') {
      steps {
        mail bcc: '', body: 'This is a test', cc: '', from: '', replyTo: '', subject: 'This is a test', to: 'serpentkekole@gmail.com'
      }
    }
  }
}


