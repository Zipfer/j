pipeline {
  agent any
  stages {
    stage('check project') {
      when {changeset "project/*"}
      steps {
        echo "Check project started"
      }
    }
    stage('Build stage') {
      steps {
        echo "Build stage"
        sh 'ls project/'
      }
    }
  }
}//
