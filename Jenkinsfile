
pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main',
                url: 'https://github.com/YOUR-USERNAME/jenkins-cicd-project.git'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                    cp index.html /var/www/html/
                    cp style.css /var/www/html/
                '''
            }
        }

        stage('Verify') {
            steps {
                sh 'echo "Deployment completed successfully!"'
            }
        }
    }
}
