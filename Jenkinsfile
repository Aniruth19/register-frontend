pipeline {
    agent any

    tools {
        nodejs "node-js" 
    }

    stages {
        stage('Install Dependencies') {
            steps {
                script {
                    sh 'npm install'
                }
            }
        }
        stage('Build') {
            steps {
                script {
                    sh 'npm run build'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    sh 'npm test'  
                }
            }
        }
    }
}
