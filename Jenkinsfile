pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "No build needed for static website"
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                sudo rm -rf /var/www/html/*
                sudo cp -r * /var/www/html/
                '''
            }
        }
    }
}
