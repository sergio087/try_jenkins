pipeline {
    agent {
        docker { image 'maven:3.5.3-jdk-8' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}