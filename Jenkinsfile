
pipeline {
    
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'ruby -v'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'docker ps'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'node -v'
            }
        }
    }
}
