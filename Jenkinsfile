@Library('my-shared-library@master') _

node
{
     stage("Clone repo") {
        git url: "https://github.com/tapasmishraarc/sample-nodejs.git"
        //fileDownloadOperation url: "https://raw.githubusercontent.com/ozlevka/go-envinronment/master/bbb.properties"
    }
    stage('Demo') {
        
                readProperties this
               
        }
        
}
