pipeline {
    agent any
    stages {
        stage('Checking python version') {
            steps {
                bat 'python -v'
            }
        }
        stage('Cloning repository') {
            steps {
                bat 'xcopy /S "*" "D:/codey/Xamp/htdocs/exp4" /Y'
            }
        }
        stage('printing done') {
            steps {
                echo 'Done'
            }
        }
    }
}
