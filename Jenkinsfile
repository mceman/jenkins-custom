pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
            echo 'building'
            echo 'done'}
        }
        stage('Test') {
            steps {
            echo 'testing'
            echo 'done'}
        }
        stage('Deploy') {
            steps {
            echo 'deploying'
            echo 'done'}
        }
    }
    post {
        always {
            echo 'post setup'
        }
    }
}
