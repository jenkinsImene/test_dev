pipeline {
  agent {
    node {
      label 'node1'
    }

  }
  stages {
    stage('node1') {
      steps {
        sh 'echco"ok"'
      }
    }

    stage('') {
      steps {
        sh 'ifconfig'
      }
    }

  }
}