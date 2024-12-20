pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git url: 'https://github.com/pichupidoo/RGR.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
