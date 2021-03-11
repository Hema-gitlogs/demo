pipeline
{
   agent any
   /*
   agent 
    {
        //label 'ubuntu'
        label 'master'
    }*/
    
    stage('Pull')
    {
       git 'https://github.com/Hema-logs/demo.git'
    }
   /* stages
    {
    stage('Build')
    {
       steps
        {
       sh 'pwd'
       dir('SpringMVCSecurityXML') 
       {
            // some block
            sh 'pwd'
            sh 'mvn clean install'
            sh 'touch file1'
       }
       sh 'pwd'
        }
    }
    stage('Deploy')
    {
        steps
        {
        dir('SpringMVCSecurityXML/target') 
       {
            // some block
            sh 'sudo cp SpringMVCSecurityXML.war /var/lib/tomcat8/webapps'
       }
        }
    }*/
    }
    
