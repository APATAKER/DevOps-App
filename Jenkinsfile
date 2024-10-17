pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'pwd'
                sh "chmod +x -R $WORKSPACE"
                sh 'ls -l'
                sh './build.sh'
                sh 'sudo docker images'
            }
        }
        stage('deploy') {
            steps {
                sh 'ls -l'
                sh './deploy.sh'
            }
        }
    }
}