pipeline {
    agent any
    stages {
        stage('Build') { steps { bat 'javac Dictionary.java' } }
        stage('Run') { steps { bat 'java Dictionary' } }
    }
}
