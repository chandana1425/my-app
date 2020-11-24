pipeline {
    agent any
    stages {
        stage('---clean-1---') {
            steps {
                sh "/opt/maven/bin/mvn clean"
            }
        }
        stage('--test-1--') {
            steps {
                sh "/opt/maven/bin/mvn test"
            }
        }
        stage('--package-1--') {
            steps {
                sh "/opt/maven/bin/mvn package"
            }
        }
    }
}
