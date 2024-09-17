pipeline {
    agent any

    stages {
        stage('Build') {
            agent {
                docker{
                   
                    
                }
            }
            steps {
                sh'''
                ls -la
                node --version
                npm --version
                npm ci
                npm run build
                ls -la
                '''
            }
        }
    }
}
