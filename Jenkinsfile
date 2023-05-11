pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'stage1 started'
        git(url: 'https://github.com/chittuarul/jenkinrepo.git', branch: 'master', changelog: true)
      }
    }

  }
}