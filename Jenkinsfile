pipeline {
    agent any
    stages {
        stage('Build HelloWorld') {
            steps {
                bat 'javac src/main/java/org/example/Hello_world.java'
                bat 'java -cp src/main/java org.example.Hello_world'
            }
        }
        stage('Build Merci') {
            steps {
                bat 'javac src/main/java/org/example/Merci.java'
                bat 'java -cp src/main/java org.example.Merci'
            }
        }
        stage('Build DeRien') {
            steps {
                bat 'javac src/main/java/org/example/DeRien.java'
                bat 'java -cp src/main/java org.example.DeRien'
            }
        }
    }
}
