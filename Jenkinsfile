pipeline {
  agent {
    docker {
      image 'python:2-alpine'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'python -m py_compile sources/add2vals.py sources/calc.py'
      }
    }
  }
}