pipeline {
    agent any
    stages {
        stage('get the code') {
            steps {
                sh 'echo "this will get me the code"'
                git 'https://github.com/devopscode1/htmlcss'
            }
        }
        stage('second stage') {
            steps {
                sh 'echo "this is second stage"'
            }
        }
        stage('third stage') {
            steps {
                sh 'echo "this is thrid step"'
            }
        }
    }
}
