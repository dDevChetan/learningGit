pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        echo 'Gitting...'
        echo 'Importing from Source'
      }
    }

    stage('Build') {
      steps {
        echo 'Building...'
        build 'Explore Git with Jenkins'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing...'
        echo 'Testing'
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
      }
    }

  }
}