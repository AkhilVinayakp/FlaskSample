pipeline {
  agent any
  stages {
    stage('print-hello') {
      steps {
        echo 'check-1'
        fileExists 'Dockerfile'
        sh 'echo `ls -la`'
      }
    }

  }
}