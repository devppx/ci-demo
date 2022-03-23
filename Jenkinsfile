pipeline {
    agent { dockerfile true }

    node("docker-slave"){
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
    }
}
