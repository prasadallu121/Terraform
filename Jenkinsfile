pipeline {
    agent any
    environment {
    def terraform = '/usr/bin'
    }
    stages {
    stage('terraform version') {
            steps {
                sh 'echo "${terraform} terraform -version"'          
            }
        }
       }
}
