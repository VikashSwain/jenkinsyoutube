pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'pwd'
          }
        }

        stage('build1') {
          steps {
            sh 'pwd'
          }
        }

      }
    }

    stage('test step') {
      steps {
        echo 'testing step'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}