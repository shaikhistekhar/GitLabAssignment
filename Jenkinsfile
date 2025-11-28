pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Compiling Java program...'
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Running Java program...'
                sh 'java HelloWorld'
            }
        }
    }
}
