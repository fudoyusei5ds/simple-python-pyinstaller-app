pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'python -m py_compile sources/add2vals.py sources/calc.py'
      }
    }
  }
}