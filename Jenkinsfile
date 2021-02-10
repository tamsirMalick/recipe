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

        stage('Package recipe project') {
                    steps {
                        sh 'mvn package -DskipTests=true'
                    }
                }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
            echo 'Someone has run my build job'
        }
    }
}
