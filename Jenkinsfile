pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                echo 'Terve'
            }
        }
        stage('Version') {
            steps {
                sh 'robot -d output tasks.robot'
            }
        }
    }
}
