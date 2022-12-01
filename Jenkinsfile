pipeline {
  agent any
  triggers {
    cron '2 * * * *'  
  }
  stages {
    stage('Hello') {
      steps {
        sh 'echo Hello World'
      }
    }
  }
}
