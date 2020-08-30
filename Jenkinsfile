pipeline {
    agent any
    tools {
        maven 'mvn3'
        jdk 'jdk1.8'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}