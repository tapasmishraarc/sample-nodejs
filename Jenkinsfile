@Library('my-shared-library@master') _
 tools {
    nodejs "nodejs" 
    }
node
{
   
    stage('Demo') {
        
        readProperties 'https://github.com/tapasmishraarc/sample-nodejs.git', this
        echo "${env.APP_NAME}"
       
        if(env.techStack == "node")
        {
            nodeBuild name:"tapas"
        }
               
        }
        
}
