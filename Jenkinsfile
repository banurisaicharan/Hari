pipeline {
    agent any

    stages {
        stage('scm checkout') {
            steps {
                git credentialsId: 'Lakshwik', url: 'https://github.com/banurisaicharan/Hari.git'
            }
        }
        stage('friend') {
            steps {
                echo "hi friend this is your friend"
            }
        }
    }
}
