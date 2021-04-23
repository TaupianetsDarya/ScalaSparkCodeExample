pipeline {
    agent any

    stages {
        stage('Test') {
           steps {
              echo "Compiling..."
              sh "${tool name: 'sbt', type:'org.jvnet.hudson.plugins.SbtPluginBuilder$SbtInstallation'}/bin/sbt compile"
           }
        }
    }
}