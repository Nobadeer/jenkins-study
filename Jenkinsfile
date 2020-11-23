pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        echo 'Foo'
        writeFile(file: 'test.sh', text: 'dummy text', encoding: 'UTF-8')
        sh 'test.sh'
      }
    }

    stage('Buzz Test') {
      steps {
        echo 'Bar'
      }
    }

  }
}