pipeline {
    agent any

    tools {
        maven 'mvn-3.9.3'
    }

    stages {
        stage('Build') {
            steps {
                echo 'steps begin.'
                sh "mvn clean package spring-boot:repackage"
                sh "printenv"
                echo 'steps end.'
           }
        }
    }
}