pipeline {
    agent any
    stages {
        stage('Build HelloWorld') {
            steps {
                sh 'javac src/main/java/org/example/Hello_world.java'
                sh 'java -cp src/main/java org.example.Hello_world'
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
