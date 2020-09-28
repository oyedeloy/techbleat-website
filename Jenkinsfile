pipeline {
    agent any
    stages {        
        stage  ('copy index file') {
            steps {
                echo "index file on it's way"
                sh 'sudo cp index.html  /usr/share/nginx/html'
            }
        }
        stage ('copy jpeg file') {
            steps {
                echo "index jpegg on it's way"
                sh 'sudo cp devops.jpg  /usr/share/nginx/html'
                
            }
        }
        stage ('task complete') {
            steps {
                echo 'job done'
            }
        }
    }
}