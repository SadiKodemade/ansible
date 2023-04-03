pipeline {
  agent any
  stages {
    stage('instalation') {
      steps {
        sh 'ansible-playbook -i inventory -m ping --auto-approve'
      }
    }

  }
}