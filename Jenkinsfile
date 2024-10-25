pipeline {
    agent { label 'linux && arm64' }
    stages {
        stage ("Builds") {
            steps {
                sh "debuild -i -us -uc -b"
            }
        }
    }
}