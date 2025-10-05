pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                // Compile the Java program
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                // Run the compiled Java program
                sh 'java HelloWorld'
            }
        }
    }
}