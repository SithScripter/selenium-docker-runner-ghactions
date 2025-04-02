pipeline{

    agent any

    stages{

        stage('Run Test'){
            steps(){
                bat "bat docker-compose up"
            }
        }

        stage('Bring Grid Down'){
            steps(){
                bat "docker-compose down"
            }
        }
    }
}