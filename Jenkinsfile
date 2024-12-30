pipeline {
    agent any

    tools {
        nodejs "node-js" 
    }

    stages {
        stage('Install Dependencies') {
            steps {
                script {
                    bat 'npm install'
                }
            }
        }
    }
}
