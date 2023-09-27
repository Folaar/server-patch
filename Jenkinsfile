pipeline {
  agent {
    label 'ansible-server'
  }
  stages {
    stage('deploy patch playbook'){
      steps{
        dir('/home/ec2-user/ansible-dev/Ansible'){
          sh 'ansible-playbook patch.yml'
        }
      }
    }
    
  }
}   
