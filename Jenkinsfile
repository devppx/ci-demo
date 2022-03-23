pipeline {
    agent { dockerfile true }

    stages {
        node("docker-slave"){
            stage('Test') {
                steps {
                    sh 'node --version'
                    sh 'svn --version'
                }
            }
        }
    }
}
