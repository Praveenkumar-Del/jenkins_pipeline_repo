pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'sleep 10'
                echo 'Building...'
                // Add your build steps here
            }
        }
        stage('Test') {
            steps {
                sh '''
                    #!/bin/bash
                    pwd
                    ls -lrt
                    sleep 5
                '''
                echo 'Testing...'
                // Add your test steps here - This is sample for Python script
                // batch '''
                //     python script.py
                // '''

            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deploy steps here
            }
        }
    }
}