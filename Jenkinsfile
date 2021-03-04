pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sshPublisher(alwaysPublishFromMaster: true, continueOnError: true, failOnError: true)
      }
    }

  }
}