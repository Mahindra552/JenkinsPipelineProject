pipeline {
    agent any
    
    stages {
        
        stage('Build')
        {
            steps {
                echo 'dev build  code'
               }
        }
        
         stage('Deploy')
           {
            steps {
                echo 'deploy code'
              }
           } 
             stage('Test')
              {
            steps {
                echo 'QA auto tests'
                    }
              }
             stage('Release')
            {
            steps {
                echo 'Release to prod'
                 }
             }
}
}
