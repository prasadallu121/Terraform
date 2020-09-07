pipeline {
    agent any 
    tools {
    tool name: 'terraform', type: 'terraform'
    }
    stages {
    stage('terraform version') {
            steps {
                sh 'terraform -version'
            }
        }
       }
}
