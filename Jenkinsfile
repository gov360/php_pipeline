pipeline {
    agent { docker 'php-alpine' }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
