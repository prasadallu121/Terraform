pipeline {
    agent any 
    stages {
    stage('GIT Checkout') {
            steps {
                git 'https://github.com/prasadallu121/Terraform.git'
            }
        }
        stage('Terraform-Init') {
            steps {
                def terraform = tool name: 'terraform', type: 'terraform'
                sh "${terraform}/usr/bin terraform init"
            }
        }
       }
}
