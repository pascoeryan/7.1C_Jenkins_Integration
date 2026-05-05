pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                echo "Building the package using Maven to compile and package the code."
            }
        }
        
        stage ('Unit and Integration tests'){
            steps{
                echo "Running unit tests with JUnit and integration tests with Selenium."
            }
        }
        
        stage ('Code Analysis'){
            steps{
                echo "Analysing code quality with SonarQube to ensure industry standards are met."
            }
        }
        
        stage ('Security Scan'){
            steps{
                echo "Performing security scan with OWASP Dependency-Check to verify vulnerabilties."
            }
        }
        
        stage ('Deploy to Staging'){
            steps{
                echo "Deploy the application to staging environment with AWS EC2 instance."
            }
        }
        
        stage ('Integration Tests on Staging'){
            steps{
                echo "Running integration tests on staging using Selenium to verify system behaviour."
            }
        }
        
        stage ('Deploy to Production'){
            steps{
                echo "Deploy the applciation to a production environment using AWS EC2 instance."
            }
        }
    }
}