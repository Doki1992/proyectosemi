pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        git(url: 'https://github.com/Doki1992/proyectosemi.git', branch: 'master')
      }
    }
    stage('deploy1') {
      steps {
        sh 'git pull'
      }
    }
  }
}