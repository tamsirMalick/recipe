node('master') {

stage('build') {
    withMaven(jdk: 'Java 8', maven: 'Maven 3.6.3') {
    sh label: '', script: 'mvn clean install'
    }
   }
}

