pipeline {
    agent any
    environment {
    def terraform = '/usr/bin'
    }
    stages {
      stage('GIT Checkout') {
            steps {
                git 'https://github.com/prasadallu121/Terraform.git'      
            }
        }
     stage('Terraform-Init') {
            steps {
                sh label: '', script: 'terraform init'    
            }
        }
       }
}
