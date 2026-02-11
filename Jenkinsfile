@Library(['exec-shared-lib', 'project-shared-lib']) _

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
