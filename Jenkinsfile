node
{
    
    stage('checkout code')
    {
        
     git 'https://github.com/AshutoshKumar99/DeployWarEC2JenkinsPipeline.git'   
    }
    
    
    
    
        
        stage('Deploy war to tomcat on ec2 machine')
        {
        sshagent(['Tomcat-Dev']) {
        sh echo "Hello world"
        }}

    
    
    
}
    

