@Library('my-shared-library@master') _

node
{
   tools { nodejs "nodejs"}
    stage('Demo') {
         
        readProperties 'https://github.com/tapasmishraarc/sample-nodejs.git', this
        echo "${env.APP_NAME}"
       
        if(env.techStack == "node")
        {
            nodeBuild name:"tapas"
        }
               
        }
        
}
