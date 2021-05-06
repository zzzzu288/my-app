pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "mvnclean"
            }
        }
        stage('--test--') {
            steps {
                sh "mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "mvn package"
            }
        }
    }
}
