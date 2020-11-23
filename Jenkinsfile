pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        writeFile(file: 'foo.txt', text: 'FOO', encoding: 'UTF8')
      }
    }

    stage('Buzz Test') {
      steps {
        echo 'Bar'
      }
    }

  }
}