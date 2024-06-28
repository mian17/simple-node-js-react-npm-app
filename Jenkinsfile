pipeline {
    agent any
    tools {
        nodejs '17.3.1'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
