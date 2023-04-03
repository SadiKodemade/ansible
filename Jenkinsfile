pipeline {
  agent any
  stages {
    stage('instalation') {
      steps {
        sh 'ansible -i inventory -m ping --auto-approve'
      }
    }

  }
}