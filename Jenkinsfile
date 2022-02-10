pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh './gradlew clean build'
      }
    }

    stage('upload') {
      steps {
        echo 'upload'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}
