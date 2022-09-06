pipeline {
    agent any
    stages{
        stage('compile stage') {
            steps {
                sh 'mvn clean compile'
            }
        }
        stage('test stage'){
            steps {
                sh 'mvn test'
            }
        }
        stage('package stage'){
            steps {
                sh 'mvn package'
            }
        }
        stage('install stage'){
            steps {
                sh 'mvn install'
            }
        }
    }
}
