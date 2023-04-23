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
                bat 'xcopy C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\devss * C:\\Xamp\\htdocs\\devops practical exp 4 /Y /S'
            }
        }
        stage('printing done') {
            steps {
                echo 'Done'
            }
        }
    }
}
