pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/sanasharma12/nginx-p.git'
            }
        }
        stage('List Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
