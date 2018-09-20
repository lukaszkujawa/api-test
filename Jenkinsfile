pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'mvn test'
            }
            steps {
                sh 'echo "everything tested.."'
            }
        }
        stage('build') {
            steps {
                sh 'echo "Build"'
                sh 'mvn --version'
            }
        }
    }
}
