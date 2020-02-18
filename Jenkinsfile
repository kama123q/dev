pipeline {
  agent {
    node {
      label 'agent { node { label \'labelName\' } }'
    }

  }
  stages {
    stage('shell') {
      steps {
        sh 'echo "this is test"'
      }
    }

  }
  environment {
    kama = '2'
    pa = '3'
  }
}