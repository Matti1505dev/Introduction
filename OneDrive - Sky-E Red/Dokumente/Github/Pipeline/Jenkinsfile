pipeline {
    agent any

    stages {
        stage("Clone from Github") {
            steps {
                sh "git clone -b develop https://github.com/Matti1505dev/Introduction.git"
            }
        }

        stage("Compress repository") {
            steps {
                sh "7z a introduction.7z ./"
            }
        }
    }
}
