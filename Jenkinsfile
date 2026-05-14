pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo "Cloning the code..."
            }
        }

        stage('Build') {
            steps {
                echo "Building project..."
                sh 'ls -l'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deployment successful!"
sh 'cat index.html'
            }
        }
    }
}
