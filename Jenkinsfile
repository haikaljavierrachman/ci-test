pipeline{
    agent any

    stages{
        stage('Build'){
            steps{
                sh 'docker build -t haikal/node-test:latest .'
            }
        }
    }
}