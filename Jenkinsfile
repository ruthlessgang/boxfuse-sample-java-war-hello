pipeline {
    agent any
    tools {
    maven 'M3'
  }

    stages {
        stage('Build') {
            steps {
                mvn clean install
                echo 'mvn done'
                sh 'mvn package'
            }
        }
    }
}
