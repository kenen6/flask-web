
Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { docker 'python:3' }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

