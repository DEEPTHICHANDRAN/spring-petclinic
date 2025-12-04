pipeline {
    agent any

    tools {
        jdk 'jdk-21'
        maven 'Maven-3'
    }

    stages {
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}
