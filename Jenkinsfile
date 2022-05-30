pipeline {
    agent {
        docker {
            image 'python:latest'
        }
    }
    stages {
        stage ('hello world') {
            steps {
                echo 'hello world'
            }
        }
        stage ('python') {
            steps {
                sh 'python --version'
            }
        }
    }
}