
pipeline {
    agent any

    triggers {
        pollSCM('H/2 * * * *')
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'Checkout completed b1'
            }
        }

        stage('Build') {
            steps {
                echo 'Build process b1'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing b1'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy b1'
            }
        }
    }
}
