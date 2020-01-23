PR=$(curl -s "${BUILD_URL}api/xml?tree=description" | perl -n -e 'print("$1\n") if m{pull/(\d+)"}')
echo PR
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'set'
            }
        }
    }
}
