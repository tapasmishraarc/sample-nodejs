library identifier: 'test@master',
    //'master' refers to a valid git-ref
    //'mylibraryname' can be any name you like
    retriever: modernSCM([
      $class: 'GitSCMSource',
      //credentialsId: 'your-credentials-id',
      remote: 'https://github.com/tapasmishraarc/jenkins-shared-library.git'
])

node
{
    stage('Demo') {
        //git url: "https://github.com/tapasmishraarc/sample-nodejs"
                readProperties this
                //echo 'Hello world'
                //echo env.techStack
               // if(env.techStack=="node"){
                 // nodeBuild name: 'tapa'
                //}
                //notify "type:'slack' message:'a slack notification'"
        }
        
}
/*pipeline {
    agent any
    tools {nodejs "nodejs"}
    stages {
        stage('Demo') {
            steps {
                readProperties this
                //echo 'Hello world'
                //echo env.techStack
               // if(env.techStack=="node"){
                 // nodeBuild name: 'tapa'
                //}
                //notify "type:'slack' message:'a slack notification'"
            }
        }
        
    }
}*/
