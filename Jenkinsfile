pipeline {
    agent { docker { image 'locustio/locust' } }
    stages {
        stage('build') {
            steps {
                sh 'locust --version'
            }
        }
    }
}
