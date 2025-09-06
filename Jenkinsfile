pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo *** SIMULATING COMPILATION WITH MAVEN ***'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                bat 'echo *** RUNNING JUNIT AND SELENIUM TESTS ***'
            }
        }
        stage('Code Analysis') {
            steps {
                bat 'echo *** RUNNING SONARQUBE ANALYSIS ***'
            }
        }
        stage('Security Scan') {
            steps {
                bat 'echo *** RUNNING OWASP DEPENDENCY CHECK ***'
            }
        }
        stage('Deploy to Staging') {
            steps {
                bat 'echo *** DEPLOYING TO AWS EC2 STAGING SERVER ***'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                bat 'echo *** RUNNING SELENIUM TESTS ON STAGING ***'
            }
        }
        stage('Deploy to Production') {
            steps {
                bat 'echo *** DEPLOYING TO AWS EC2 PRODUCTION SERVER ***'
            }
        }
    }
}