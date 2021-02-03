node('master') {

stage('build') {
    withMaven(jdk: 'Java 8', maven: 'Maven 3.6.3') {
    bat label: '', script: 'mvn clean install'
    }
   }
}

