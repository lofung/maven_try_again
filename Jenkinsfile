pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Checkout the repository
                checkout scm

                // Build the Maven project
                bat 'mvn build'
            }
        }
    }
}
