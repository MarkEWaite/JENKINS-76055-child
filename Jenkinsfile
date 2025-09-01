pipeline {
    agent any

    stages {
        stage('Show README') {
            steps {
                checkout scm
                sh 'cat README.md'
            }
        }
    }
}

