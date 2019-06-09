pipeline {
    agent { docker run -d --name myalpine alpine sh 'top'}
    stages {
        stage('build') {
            steps {
                sh 'docker inspect myalpine'
            }
        }
    }
}
