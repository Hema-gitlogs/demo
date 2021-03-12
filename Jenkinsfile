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
       steps
       {
            sh 'mvn clean install'
       }
    }
    stage('Deploy')
    {
        steps
        {
           sh 'mv target/*.war javademoex.war 
           sh 'sudo cp  javademoex.war /var/lib/tomcat9/webapps'
        }
    }
    }
}
