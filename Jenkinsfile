pipeline {
  agent any
  stages {
    stage('instalation') {
      steps {
        ansiblePlaybook(become: true, playbook: 'playbook', inventory: 'inventory', sudo: true)
      }
    }

  }
}