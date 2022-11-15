pipeline {
  agent any
  triggers {
    cron '1 * * * *'  
  }
  stages {
    stage('Hello') {
      steps {
        sh 'echo Hello World'
      }
    }
  }
}
