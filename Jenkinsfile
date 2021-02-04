pipeline {
    agent any
    tools {
        maven 'maven363'
    }
    stages {
        stage('Test maven project') {
            steps {
                sh 'mvn test'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}