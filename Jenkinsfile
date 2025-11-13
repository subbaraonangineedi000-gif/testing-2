pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running the Python application...'
                sh 'python3 app.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'python3 -m unittest test_app.py'
            }
        }
    }
}
