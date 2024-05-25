pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the Git repository
                git 'https://github.com/ria0308/vs_mkr_test1'
            }
        }
        stage('Build') {
            steps {
                // Dummy build step
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                // Dummy test step
                echo 'Testing...'
            }
        }
    }
    post {
        always {
            echo 'Pipeline has finished'
        }
        success {
            echo 'Pipeline succeeded'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}
