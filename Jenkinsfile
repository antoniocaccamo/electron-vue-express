pipeline {
  agent any
  stages {
    stage('scm') {
      steps {
        git(credentialsId: 'antoniocaccamo', url: 'git@github.com:antoniocaccamo/spring-boot-camel-sample.git', branch: 'master')
      }
    }

  }
}