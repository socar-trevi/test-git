pipeline {
  agent any
  triggers {
    cron '5 * * * *'  
  }
  stages {
    stage('Hello') {
      steps {
        sh 'echo Hello World'
      }
    }
  }
}
