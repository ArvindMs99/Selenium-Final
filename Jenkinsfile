pipeline {
    agent any
    stages {
        stage('BUILD') {
            steps {
                echo 'BUILDED'
            }
        }
        stage('DEPLOY') {
            steps {
                echo 'DEPLOYED'
            }
        }
        stage('TEST') {
            steps {
                bat 'locust'
                echo 'TESTED'
            }
        }
        stage('RELEASE') {
            steps {
                echo 'RELEASED'
            }
        }
    }
}
