pipeline {
    agent any 
    tool name: 'terraform', type: 'terraform'
    stages {
        stage('GIT Checkout') {
            steps {
                git 'https://github.com/prasadallu121/Terraform.git'
            }
        }
        stage('Terraform-Init') {
            steps {
                sh 'sh label: '', script: 'terraform init'
            }
        }
       }
}
