pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "building"
                bat "mvn --version"
                bat 'set'
            }
        }
    }
}