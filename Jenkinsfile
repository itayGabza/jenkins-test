  
pipeline {
  agent any

  stages {
    stage('Git Clone') {
      steps {
        sh 'echo \'Git cloning\''
        sh 'git clone https://github.com/itayGabza/jenkins-test.git' 
      }
    }

    stage('Yarn install') {
      steps {
        sh 'echo \'build\''
        sh 'yarn install'
      }
    }
    stage('Yarn build') {
      steps {
        sh 'echo \'build\''
        sh 'yarn build'
      }
    }
  }
}
