pipeline {
  agent any
  stages {
    stage('build') {
      steps{
      sh "'${mvnHome}/bin/mvn' -Dmaven.test.failure.ignore clean"
      }

    }
  }
}
