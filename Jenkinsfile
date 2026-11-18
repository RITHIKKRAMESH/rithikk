pipeline {
    agent any

    stages {

        stage('Compile') {
            steps {
                sh 'javac rithikk.java'
            }
        }

        stage('Execute') {
            steps {
                sh 'echo 10 | java Main'
            }
        }
    }
}
