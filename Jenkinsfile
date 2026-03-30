pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                echo "Cloning repository..."
            }
        }

        stage('Build') {
            steps {
                sh 'echo "This is real build step"'
                sh 'ls -l'
            }
        }
    }
}
