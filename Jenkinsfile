pipeline {
  agent any
  stages {
    stage('List Files') {
      steps {
        bat '''
                C:
                cd \\
                dir
                '''
      }
    }

    stage('Data Factory') {
      agent any
      steps {
        echo 'bonjour'
        echo 'bonsoir'
      }
    }

  }
}