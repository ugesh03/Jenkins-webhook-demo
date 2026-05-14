pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo "Cloning the code..."
sh 'cd /home'
sh 'git clone https://github.com/ugesh03/Jenkins-webhook-demo.git'
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
