pipeline {
  agent any
  stages {
    stage('Setup Gateway') {
      steps {
        sh 'ansible-playbook --vault-pass-file=~/.ansible_pass setup-gateway.yml'
      }
    }
  }
}
