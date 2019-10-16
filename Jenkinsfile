Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker '3.7.4' }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
