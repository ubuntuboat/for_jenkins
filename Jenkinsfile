pipeline {
    agent any

    tools {
        maven 'mvn-3.5.4'
    }

    stages {
        stage('Build') {
            steps {
                echo 'steps begin.'
                sh "mvn clean package sprint-boot:repackage"
                sh "printenv"
                echo 'steps end.'
           }
        }
    }
}