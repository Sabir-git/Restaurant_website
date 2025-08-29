pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Sabir-git/Restaurant_website.git'
            }
        }

        stage('Build') {
            steps {
                echo "No build needed for static HTML & CSS"
            }
        }

        stage('Test') {
            steps {
                echo "We could run HTML/CSS validators here"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying website files..."
                sh 'cp -r * /var/www/html/'  // Example: copy files to web server folder
            }
        }
    }
}
