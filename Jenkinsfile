  
pipeline {
  agent any

  stages {
    stage('Git Clonee') {
      steps {
        sh 'echo \'Git cloning\''
        sh 'git branch: 'main', credentialsId: '8dca5a14-6d7e-4fed-acd1-c918a89b2c2c', url: 'https://github.com/Click-Ins/Backoffice.git'' 
      }
    }

    stage('Yarn install') {
      steps {
        sh 'echo \'build\''
        // sh 'yarn install'
      }
    }
    stage('Yarn build') {
      steps {
        sh 'echo \'build\''
        // sh 'yarn build'
      }
    }
  }
}
