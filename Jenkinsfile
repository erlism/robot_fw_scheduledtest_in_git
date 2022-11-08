pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Version') {
            steps {
                sh 'rcc run'
            }
        }
    }
}
