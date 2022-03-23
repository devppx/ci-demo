pipeline {
    agent { 
        label 'docker-slave'
    }

    stages {
        stage('Test') {
            agent {
                dockerfile true 
            }
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
