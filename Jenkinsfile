pipeline {
    agent any
    stages {
        stage('Build HelloWorld') {
            steps {
                sh 'javac src/main/java/org/example/HelloWorld.java'
                sh 'java -cp src/main/java org.example.HelloWorld'
            }
        }
        stage('Build Merci') {
            steps {
                sh 'javac src/main/java/org/example/Merci.java'
                sh 'java -cp src/main/java org.example.Merci'
            }
        }
        stage('Build DeRien') {
            steps {
                sh 'javac src/main/java/org/example/DeRien.java'
                sh 'java -cp src/main/java org.example.DeRien'
            }
        }
    }
}
