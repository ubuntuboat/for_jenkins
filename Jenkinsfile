pipeline {
    agent any

    toos {
        maven 'mvn-3.5.4'
    }

    stages {
        stage('Build') {
            steps {
                echo 'lightboat begin.'
                sh "mvn clean package sprint-boot:repackage"
                sh "printenv"
                echo 'lightboat begin.'
           }
        }
    }
}