pipeline {
    agent { docker { image 'python:3.11.5-alpine3.18' } }
    stages {
        stage('build') {
            steps {
                script {
                    sh 'python -c "print(\'Bye, World!\')"'
                }
            }
        }
    }
}
