pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'sbt test'
                }
            }
        stage('Test') {
            steps {
                sh 'sbt test'
            }
        }
    }
}