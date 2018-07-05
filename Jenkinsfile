node
{
    
    stage('deploy')
    {
        
         stage('Deploy war to tomcat on ec2 machine')
    {
        sshagent(['Tomcat-Dev']) {
       sh 'scp -o StrictHostKeyChecking=no target **/*.war ec2-user@52.66.56.87:/usr/share/tomcat7/webapps/'
}

    }
    }
    
}
