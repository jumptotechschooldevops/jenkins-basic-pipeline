pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code pulled from GitHub'
                checkout scm
            }
        }

        stage('Run Script') {
            steps {
                sh './hello.sh'
            }
        }
    }
}
