#!/usr/bin/env groovy

pipeline {
    agent any
    tools {
        nodejs 'node-8.1.3'
    }
    stages {
        stage('Build') {
            steps {
                sh 'nodejs --version'
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'nodejs --version'
                echo "This project is tested"
            }
        }
    }
}
