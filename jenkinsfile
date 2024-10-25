pipeline {
    agent { label 'linux && arm64' }
    stages {
        stage ("Builds") {
            steps {
                sh "pwd && debuild -i -us -uc -b"
            }
        }
    }
}