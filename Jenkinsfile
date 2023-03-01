pipeline{
    agent any

    stages{
        stage('Build'){
            steps{
                sh 'docker built -t haikal/node-test:latest .'
            }
        }
    }
}