pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
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