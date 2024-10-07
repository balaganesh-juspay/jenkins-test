pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Execute the xcodebuild command
                sh 'xcodebuild -version'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Add test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment commands here
            }
        }
    }
}
