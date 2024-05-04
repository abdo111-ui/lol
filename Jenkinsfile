pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hi build stage'
        input(message: 'are u ok', ok: 'ok')
      }
    }

  }
}