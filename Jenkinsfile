pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        echo 'branch indexing'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            bat 'mvn -v'
          }
        }

        stage('functionaltest') {
          steps {
            bat 'java -version'
          }
        }

      }
    }

  }
}