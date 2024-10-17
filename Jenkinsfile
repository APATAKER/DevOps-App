pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh "chmod +x -R $WORKSPACE"
                sh 'ls -l'
                sh './build.sh'
            }
        }
    }
}