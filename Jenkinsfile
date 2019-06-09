pipeline {
    agent { docker 'webstream/php-alpine' }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
