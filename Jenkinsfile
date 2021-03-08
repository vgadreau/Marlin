pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh '/root/.platformio/penv/bin/pio build'
            }
        }
    }
}