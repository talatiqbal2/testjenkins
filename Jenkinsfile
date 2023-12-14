pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      steps {
        echo 'Fluffy Build'
        sh 'echo Edited Placeholder'
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