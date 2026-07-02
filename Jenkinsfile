pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: https://github.com/likithaiyengar/external.git'
            }
        }

        stage('Status') {
            steps {
                echo "Build Successful"
            }
        }
    }
}
