pipeline{
   agent any
   tools{
       maven "maven-3.9.10"
   }
    stages{
        stage('code checkout')
        {
            steps
            {
                git branch: 'dev1', url: 'https://github.com/Hari966671/maven-webapplication-project-kkfunda.git'
            }
           }
           stage('code compile')
           {
               steps
               {
                  sh "mvn compile"
               }
           }
        }
    }
    
