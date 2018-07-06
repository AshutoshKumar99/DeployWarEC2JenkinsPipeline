node
{
    
    stage('checkout code')
    {
        
     git 'https://github.com/AshutoshKumar99/DeployWarEC2JenkinsPipeline.git'   
    }
    
    
    
    
        
        stage('Deploy war to tomcat on ec2 machine')
        {
        sshagent(['Tomcat-Dev']) {
        sh 'scp -o StrictHostKeyChecking=no  sample.war ec2-user@52.66.56.87:/usr/share/tomcat7/webapps/'
        }}

    
    
    
}
    

