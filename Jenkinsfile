pipeline {
    agent any
    stages {
        stage('Build') {
            tools {
                dotnetsdk 'dotnet-sdk-6.0'
            }
            steps {
                echo 'Building..'
                sh '''
                dotnet build
                '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh '''
                echo "Testing Successfull.."
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}
