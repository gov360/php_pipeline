pipeline {
    agent { docker 'lebr1/php-alpine' }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
