pipeline {
    agent any
    tools {
    maven 'M3'
  }

    stages {
        stage('Build') {
            steps {
                mvn clean install
                sh 'mvn package'
            }
        }
    }
}
