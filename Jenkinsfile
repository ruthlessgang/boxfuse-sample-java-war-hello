pipeline {
    agent any
    tools {
    maven 'M2'
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
