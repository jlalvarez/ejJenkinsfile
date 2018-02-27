pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                ruby -v
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                docker ps
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                node -v
            }
        }
    }
}