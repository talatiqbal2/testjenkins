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

    stage('Deploy') {
      steps {
        echo 'Deploying...'
      }
    }

    stage('error') {
      steps {
        echo 'hello this is my message'
      }
    }

    stage('Fluffy Build') {
      steps {
        echo 'Fluffy Build'
        sh 'echo Another Placeholder'
      }
    }

    stage('Fluffy Test') {
      steps {
        echo 'Fluffy build'
        sh '''sleep 5
echo Success!'''
      }
    }

    stage('Fluffy Deploy') {
      steps {
        echo 'Fluffy Deploy '
      }
    }

  }
}