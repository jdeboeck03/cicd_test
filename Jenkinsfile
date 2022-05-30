pipeline {
    agent {
        docker {
            image 'python:latest'
        }
    }
    stages {
        stage ('python') {
            steps {
                sh 'python --version'
            }
        }
    }
}