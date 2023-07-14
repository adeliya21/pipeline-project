pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Welcome to Jenkins World'
                sh 'pyhton --version'
                sh 'python pipeline.py'
            }
        }
    }
}