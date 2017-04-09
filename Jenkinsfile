pipeline {
  agent any
  stages {
    stage('Clean') {
      steps {
        ws(dir: 'blewotion_ws') {
          sh '''echo "~> Running on host, "
hostname'''
        }
        
      }
    }
  }
}