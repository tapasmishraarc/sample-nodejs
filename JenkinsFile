library identifier: 'mylibraryname@master',
    //'master' refers to a valid git-ref
    //'mylibraryname' can be any name you like
    retriever: modernSCM([
      $class: 'GitSCMSource',
      //credentialsId: 'your-credentials-id',
      remote: 'https://github.com/tapasmishraarc/jenkins-shared-library.git'
])

pipeline {
    agent any
    tools {nodejs "nodejs"}
    stages {
        stage('Demo') {
            steps {
                //echo 'Hello world'
                nodeBuild name: 'tapa'
                //notify "type:'slack' message:'a slack notification'"
            }
        }
    }
}
