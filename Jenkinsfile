pipeline {
    agent any
    environment {
    def terraform = '/usr/bin'
    }
    stages {
    stage('terraform version') {
            steps {
                echo "${terraform} terraform -version"            }
        }
       }
}
