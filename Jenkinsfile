pipeline {
    agent { docker { image 'node' } }
    stages {
        stage('build') {
            steps {
                echo 'Hi world'
                sh 'npm --version'
            }
        }
    }
}
