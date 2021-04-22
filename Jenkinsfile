pipeline {
    agent {
        docker {
            image 'hseeberger/scala-sbt'
        }
    }
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