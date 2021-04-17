@Library('my-shared-library@master') _

pipeline {
  agent any
 
  tools {nodejs "nodejs"}
 
  stages {
    stage('Example') {
      steps {
        readProperties 'https://github.com/tapasmishraarc/sample-nodejs.git', this
        echo "${env.APP_NAME}"
       
        
      }
    }
  }
}

