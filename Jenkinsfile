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
                sh 'sh label: '', script: 'terraform init'
            }
        }
        stage('Terraform-Validate') {
            steps {
                sh label: '', script: 'terraform validate'
            }
        }
        stage('Terraform-Plan') {
            steps {
                sh 'sh label: '', script: 'terraform plan'
            }
        }
    }
}
