
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage started'
                sh 'echo Building application'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage started'
                sh 'echo Running tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage started'
                sh 'echo Deploying application'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}
