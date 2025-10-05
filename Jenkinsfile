pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                // Compile the Java program
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                // Run the compiled Java program
                bat 'java HelloWorld'
            }
        }
    }
}