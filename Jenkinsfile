pipeline {
    agent any

    tools {
        maven 'mvn-3.9.3'
    }

    stages {
        stage('Build') {
            steps {
                echo 'steps begin.'
                bat "mvn clean package spring-boot:repackage"
                bat "printenv"
                echo 'steps end.'
           }
        }
    }
}