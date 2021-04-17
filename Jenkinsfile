@Library('my-shared-library@master') _

node
{
   
    stage('Demo') {
         tools { nodejs "nodejs"}
        readProperties 'https://github.com/tapasmishraarc/sample-nodejs.git', this
        echo "${env.APP_NAME}"
       
        if(env.techStack == "node")
        {
            nodeBuild name:"tapas"
        }
               
        }
        
}
