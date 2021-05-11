  
pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        sh 'echo \'Welcome\''
        sh 'git clone https://github.com/itayGabza/jenkins-test.git' 
      }
    }

    stage('Pack') {
      steps {
        sh 'echo \'build\''
      }
    }
  }
}
