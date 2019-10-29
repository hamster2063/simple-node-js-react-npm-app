pipeline {
    agent any
    
    stages {
        stage ('Say Hello To the World') {
          steps {
            checkout scm
          }
        }        
        stage('Build') {
            steps {
                sh "apk add nodejs"
                sh "echo $PATH"
                sh 'npm install'
            }
        }
    }
}
