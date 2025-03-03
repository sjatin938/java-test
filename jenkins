pipeline{
    agent any 
    stages{
        stage('Compile Stage'){
            steps{
               bat javac Test.java
            }
        }
        stage('Run Stage'){
            steps{
               bat java Test.java
            }
        }
    }
}