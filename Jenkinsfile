pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Jenkins from GitHub'
            }
        }

        stage('Server Info') {
            steps {
                sh 'whoami'
                sh 'pwd'
                sh 'ls -l'
            }
        }
    }
}
