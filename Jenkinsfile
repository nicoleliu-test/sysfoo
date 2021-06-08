pipeline {
  agent {
    docker {
      image 'maven:3.6.3-jdk-11-slim'
    }

  }
  stages {
    stage('build') {
      steps {
        build 'build'
        echo 'compile maven app'
      }
    }

    stage('test') {
      steps {
        echo 'test maven app'
      }
    }

    stage('package') {
      steps {
        sleep 1
        echo 'package maven app'
      }
    }

  }
}