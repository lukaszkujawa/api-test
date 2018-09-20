pipeline {
    agent { docker { image 'maven:3.3.3' } }
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
