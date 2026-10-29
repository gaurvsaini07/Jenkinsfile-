
pipeline {
    agent any

    triggers {
        pollSCM('H/2 * * * *')
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'Checkout completed b1 hh'
            }
        }

        stage('Build') {
            steps {
                echo 'Build process b1 hh'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing b1 hh'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy b1 hh'
            }
        }
    }
}
