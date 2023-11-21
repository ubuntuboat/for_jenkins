pipeline {
    agent any

//    tools {
//        maven 'mvn-3.9.3'
//    }

    stages {
        stage('Build') {
            steps {
                echo 'steps begin.'
                bat "mvn clean package spring-boot:repackage"
                bat "set"
                echo 'steps end~~~'
           }
        }
        
        stage('Echo') {
        	steps {
        		echo 'try a try.'
        	}
        }
    }
}
