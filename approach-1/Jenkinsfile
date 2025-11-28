pipeline{

    agent any

    stages{

        stage('Run Test'){
            steps{
                ch "docker-compose up"
            }
        }
        stage('Bring Grid Down'){
            steps{
                echo "docker-compose down"
            }
        }
}