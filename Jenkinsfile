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
       dir('main') 
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
        dir('main') 
       {
            // some block
            sh 'sudo cp main.war /var/lib/tomcat9/webapps'
       }
        }
    }*/
    }
    
