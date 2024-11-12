pipeline {
    agent {
        docker {
            image 'python:latest'
            args '-u root'
        }
    }
    stages {
        stage('requs') {
            steps {
                script {
                    sh 'pip install -r requirements.txt'
                }
            }
        }
    }
}
