pipeline {
    agent any
    environment {
    def terraform = '/usr/bin'
    }
    options {
    timestamps()
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
      stage('Terraform-Apply') {
            steps {
                sh label: '', script: 'terraform destroy --auto-approve'    
            }
        }
       }
}
