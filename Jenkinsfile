pipeline {
  agent any
  triggers {
    cron '15 * * * *'  
  }
  stages {
    stage('Hello') {
      steps {
        sh 'echo Hello World'
      }
    }
  }
}
