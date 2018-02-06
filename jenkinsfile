pipeline {
  agent any
  stages {
    stage('build') {
    sh "'${mvnHome}/bin/mvn' -Dmaven.test.failure.ignore clean "
    }
  }
}
