pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('lint') {
      steps {
        echo 'holi'
      }
    }

    stage('build') {
      steps {
        echo 'building'
      }
    }

    stage('unit test') {
      agent any
      environment {
        ENV = 'value'
      }
      steps {
        echo 'unit test'
      }
    }

  }
}