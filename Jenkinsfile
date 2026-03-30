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
                sh 'echo "Building project..."'
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }

      stage('Deploy') {
    steps {
        sh '''
        cp index.html /var/www/html/
        '''
    }
}
    }
}
