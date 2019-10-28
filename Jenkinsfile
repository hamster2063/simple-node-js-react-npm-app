pipeline {
    agent any
    tools {
        nodejs 'NodeJS 13.0.1'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
