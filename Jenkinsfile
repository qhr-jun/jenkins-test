pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'set'
                bat "echo ${env.CHANGE_ID}"
            }
        }
    }
}
