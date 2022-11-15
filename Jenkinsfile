pipeline {
  agent any
  triggers {
    cron '* * * * *'  
  }
  stages {
    stage('Hello') {
      steps {
        sh 'echo Hello World'
      }
    }
  }
}
