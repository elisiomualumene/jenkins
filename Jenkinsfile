pipeline {
    agent any

    stages {
        stage("Build Docker Image") {
            steps{
                sh 'echo "Executando o comando docker build"'
            }
        }

        stage("List all files") {
            steps{
                sh "ls"
            }
        }
    }
}