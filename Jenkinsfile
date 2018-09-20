pipeline {
    agent any
    stages {
        stage('test') {
            sh 'echo "Test"'
        }
        stage('build') {
            steps {
                sh 'echo "Build"'
                sh 'mvn --version'
            }
        }
    }
}
