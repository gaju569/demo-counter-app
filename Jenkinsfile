pipeline{
    agent any
    
    stages{

        stage('git checkout'){

        


            steps{
                git branch: 'main', url: 'https://github.com/gaju569/demo-counter-app.git'
            }
        }
        stage('maven build'){

            steps{
                sh 'mvn clean install'
            }
        }        

    }        
                
}    
