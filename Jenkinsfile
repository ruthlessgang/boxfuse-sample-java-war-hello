pipeline {
    agent any
    tools {
    
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
