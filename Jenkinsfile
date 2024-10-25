pipeline {
    agent { label 'linux && arm64' }
    stages {
        stage ("Builds") {
            steps {
                sh "echo hello"
                sh "pwd && debuild -i -us -uc -b"
            }
        }
    }
}