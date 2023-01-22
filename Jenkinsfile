pipeline{
    agent any
    stages{
        stage('git checkout'){
            steps{
             git branch: 'main', url: 'https://github.com/81062/javaproject22.git'   
            }
            
        }
        stage('build'){

            steps{
                sh 'mvn clean'
            }
        }
    }
}