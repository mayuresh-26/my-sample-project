pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning code...'
            }
        }

        stage('Build') {
            steps {
                echo 'Build step (can be compiling, etc.)'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'python3 app.py'
            }
        }
    }
}

