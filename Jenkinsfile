// Jenkinsfile (place in root of repo)
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building branch: ${env.main}"
            }
        }

        stage('Test') {
            steps {
                echo "Running tests for branch: ${env.main}"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying branch: ${env.main}"
            }
        }
    }
}
