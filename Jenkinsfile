@Library('my-shared-library@master') _

pipeline {
  agent any
 
  tools {nodejs "nodejs"}
  parameters {
        string(name: 'url', defaultValue: 'https://github.com/tapasmishraarc/sample-nodejs.git', description: 'Who should I say hello to?')
    }
  stages {
    stage('Example') {
      steps {
        readProperties "${params.url}", this
        echo "${env.APP_NAME}"
       
        
      }
    }
  }
}

