pipeline {
    agent any

    tools{
        maven 'mvn'
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }

        stage('Code Quality') {
            steps {
                echo 'Code Quality..'
            }
        }    
        stage('Deploy to Dev') {
            steps {
                echo 'Deploy Dev..'
            }
        }    
        stage('Deploy to UAT') {
            steps {
                echo 'Deploy to UAT..'
            }
        }
        stage('Deploy to Prod') {
            steps {
                echo 'Prod Deployment....'
            }
        }
    }
}