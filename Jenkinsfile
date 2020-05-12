pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(url: 'https://github.com/kumar0608/test1.git', branch: 'master')
      }
    }

    stage('build') {
      steps {
        echo 'hello'
      }
    }

  }
}