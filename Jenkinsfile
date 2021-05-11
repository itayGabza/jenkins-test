  
pipeline {
  agent any

  stages {
    stage('Git Clonee') {
      steps {
        sh 'echo \'Git cloning\''
        sh 'git status' 
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
