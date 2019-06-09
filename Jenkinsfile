pipeline {
    agent { docker run -d -name myalpine 'alpine' }
    stages {
        stage('build') {
            steps {
                sh 'docker inspect myalpine'
            }
        }
    }
}
