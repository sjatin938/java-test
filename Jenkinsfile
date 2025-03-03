pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               bat 'echo "Hello World"'
            }
        }
        stage('Build') {
            steps {
               bat 'javac Test.java'  // Compile Java file
            }
        }
        stage('Test') {
            steps {
               bat 'java Test'  // Run the compiled Java class
            }
        }
    }
}
