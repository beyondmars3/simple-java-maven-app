pipeline {
    agent any
    tools {
        maven 'mvn3'
        jdk 'jdk1.8'
    }
    stages {
        stage('one') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}