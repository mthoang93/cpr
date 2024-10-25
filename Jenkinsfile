pipeline {
    agent { label 'linux && arm64' }
    stages {
        stage ("Builds") {
            steps {
                sh "echo start build"
                sh "pwd && debuild -i -us -uc -b"
            }
        }
    }
}