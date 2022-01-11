pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        echo 'branch indexing'
      }
    }

    stage('test') {
      steps {
        bat 'mvn -v'
      }
    }

  }
}