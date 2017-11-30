pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat(returnStdout: true, returnStatus: true, script: 'mvn -Dmaven.test.skip=true clean package')
      }
    }
  }
}