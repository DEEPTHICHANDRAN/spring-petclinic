pipeline {
    agent any

    tools {
        jdk 'jdk-21'
        maven 'Maven-3'
    }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
