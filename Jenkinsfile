pipeline {
    agent any

    stages {
        stage('Install') {
            steps {
                bat 'npm install'
            }
        }

        stage('Lint') {
            steps {
                bat 'npm run lint'
            }
        }

        stage('Test') {
            steps {
                bat 'npm test'
            }
        }
    }
}

