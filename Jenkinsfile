pipeline {
    agent any 
    tools {
    def terraform = tool name: 'terraform', type: 'terraform'
    }
    stages {
    stage('terraform version') {
            steps {
                sh 'terraform -version'
            }
        }
       }
}
