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
                sh "apk add --update nodejs nodejs-npm"
                sh "apk add nodejs"
                sh "apk add nodejs-npm"
                sh "echo $PATH"
                sh 'npm install'
            }
        }
    }
}
