pipeline {
    agent {
        docker {
            image 'node:20'
        }
    }

    stages {
        stage('Check Node') {
            steps {
                sh 'node -v'
                sh 'npm -v'
                sh 'pwd'
                sh 'ls -la'
            }
        }
    }
}