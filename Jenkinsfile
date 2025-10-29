pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning the repository...'
                git 'https://github.com/poojamorabagi31-arch/git-jenkins-integrate.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
               
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Example deployment step
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
