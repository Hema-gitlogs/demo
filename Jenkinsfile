pipeline
{
   agent any
   /*
   agent 
    {
        //label 'ubuntu'
        label 'master'
    }*/
    stages
    {
    stage('Pull')
    {
       git 'https://github.com/Hema-logs/demo.git'
    }
  
    stage('Build')
    {
            sh 'mvn clean install'
       
    }
    stage('Deploy')
    {
        steps
        {
            sh 'sudo cp target/*.war /var/lib/tomcat9/webapps'
        }
    }
    }
}
