pipeline {
    agent any
    tools {
        nodejs 'NodeJS 22.3.0'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
