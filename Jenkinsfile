@Library('exec-shared-lib') _
@Library('project-shared-lib') _

pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        script {
          PERMavenlib(name: 'demo-app-jen')
        }
      }
    }
  }
}
