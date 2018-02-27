# Ejemplo Jenkinsfile

pipeline {
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}
