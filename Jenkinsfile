@Library('my-shared-library@master') _

pipeline {
  agent any
 
  tools {nodejs "node"}
 
  stages {
    stage('Example') {
      steps {
        readProperties 'https://github.com/tapasmishraarc/sample-nodejs.git', this
        echo "${env.APP_NAME}"
       
        if(env.techStack == "node")
        {
            nodeBuild name:"tapas"
        }
      }
    }
  }
}

