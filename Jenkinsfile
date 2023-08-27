pipeline {
    agent {
        docker {
            image 'node:lts'
            args '-p 3000:3000'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
        stage('test') {
            steps {
                echo 'testing...'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying...'
            }
        }
    }
}
