pipeline {
    agent any 
    stages {
        stage('GIT Checkout') {
            steps {
                sh 'mvn -B clean verify'
            }
        }
        stage('Example Build') {
            steps {
                sh 'mvn -B clean verify'
            }
        }
    }
}
