pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Shreyashh09/jenkins-git-demo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
