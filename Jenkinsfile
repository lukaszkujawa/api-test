pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World"'
                sh 'echo $PATH'
                sh 'mvn --version'
            }
        }
    }
}
