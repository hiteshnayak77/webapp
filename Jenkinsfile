pipeline {
    agent any
    stages{
        stage('compile stage') {
            steps {
                sh 'mvn install'
            }
        }
        stage('package stage'){
            steps {
                echo "hello"
            }
        }
        stage('install stage'){
            steps {
                echo "hi"
            }
        }
    }
}
