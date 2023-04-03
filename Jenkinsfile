pipeline {
  agent any
  stages {
    stage('instalation') {
      steps {
        sh 'ansible all -i inventory -m ping --auto-approve'
      }
    }

  }
}