pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
                sh 'ls -l'
                sh 'pwd'
                sh "chmod +x -R $WORKSPACE"
                sh 'ls -l'
                sh './build.sh'
            }
        }
    }
}