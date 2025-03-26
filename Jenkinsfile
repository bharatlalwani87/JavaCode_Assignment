pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the public Git repository
                git url: 'https://github.com/bharatlalwani87/JavaCode_Assignment.git'
            }
        }

        stage('Compile') {
            steps {
                // Compile the Java code
                sh 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                // Run the compiled Java program
                sh 'java Hello'
            }
        }
    }
}