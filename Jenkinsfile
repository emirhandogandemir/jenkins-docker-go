pipeline {
    agent any
    
   
    stages {
        stage('checkout'){
            steps{
                checkout scm 
            }
        }
        
         stage('Static Code Analysiz'){
            steps{
                echo 'static analysiz'
            }
        }
        stage('Test') {
            steps {
                echo 'testler calisti'
            }
        }
        stage('Build'){
             steps{
                sh 'docker build -t first-build ..'
                
            }
        }
         stage('Deploy'){
             steps{
                echo "deploy süreci ..."
                
            }
        }
          
    }
}

